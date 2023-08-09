# Home Assistant Add-on: HassBox 外网访问

可从`HassBox`微信公众号免费申请外网访问链接！

`原理`：将域名映射到本机 IPv6 地址，本地使用 acme.sh 生成 SSL 证书，结合 NGINX Web 服务器并设置 SSL 代理，从而实现 外网访问 + 本地访问 共存模式。免费的 SSL 证书有效期一般为两个月，插件会在到期前一天自动重新生成新的 SSL 证书。

`注意`：本地网络需支持 IPv6，且设备能获取到公网 IPv6 地址。

![Supports aarch64 Architecture][aarch64-shield] ![Supports amd64 Architecture][amd64-shield] ![Supports armhf Architecture][armhf-shield] ![Supports armv7 Architecture][armv7-shield] ![Supports i386 Architecture][i386-shield]

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[discord]: https://discord.gg/c5DvZ4e
