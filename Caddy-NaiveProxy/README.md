本例为使用 Caddy 的改进版 forwardproxy 插件实现的 NaiveProxy 服务端应用，默认配置自动申请 TLS 证书和重定向到 HTTPS。

使用本例的 NaiveProxy 支持 HTTP/3 传输，若想要由 Caddy 处理的 HTTP/3 应用高速传输，建议[增加服务端系统的 UDP 缓冲区大小](https://github.com/quic-go/quic-go/wiki/UDP-Buffer-Sizes)。
