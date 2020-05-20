# 调试相关

```
// 调试 NPM
{
  "type": "node",
  "request": "launch",
  "name": "gulp h5",
  "skipFiles": [
    "<node_internals>/**"
  ],
  "console": "integratedTerminal",
  "runtimeExecutable": "npm", //runtimeExecutable表示要使用的运行时，默认为node，这里我们配置成了npm
  "runtimeArgs": [
    "run-script", "gulp-test"    //这里的dev就对应package.json中的scripts中的dev
  ]
}
```