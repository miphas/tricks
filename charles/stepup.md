
1. 安装 charles-dmg 包
2. SSL Proxying -> Install Charles Root Certificate
3. 钥匙串中选择 信任 - 使用此证书时始终信任
4. 代理本机的 HTTPS 请求
    - proxy -> SSL proxying Setting
    - Add *:443
5. 代理手机的请求
    - SSL Proxying -> Install Certificate on A mobile device
    - 按照提示操作 (wifi 配置代理)
    - 手机访问 chls.pro/ssl 下载描述符
    - 设置 - 通用 - 描述符文件与设备管理 - 安装证书
    - 设置 - 关于本机 - 证书信任设置 - 开启 Charles-Proxy-CA