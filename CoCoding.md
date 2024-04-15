# Co-coding 扩展功能

## 本地开发
> `go get -u` 更新开发包
- 启动Web服务
`go env -w CGO_ENABLED="0" && go run main.go run`
- 测试
打开网址

- 错误处理
iostat_darwin.c:28:2: warning: 'IOMasterPort' is deprecated

- 升级go1.22.2
- go mod tidy

## 添加功能

- 快捷配置
> 快捷配置能够配置一些常用参数，例如：入站端口范围、入站TLS证书，以免每次添加入站节点时需要手动输入。

- 节点复制
> 入站节点操作增加复制功能，可以快速复制节点信息，端口和ID会重新生成，主要复制TLS证书信息。
