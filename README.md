# NTLM Proxy Example

start proxy (vendor directory) with user credentials in flags.

```shell
cd vendor/github.com/jbussdieker/go-ntlm-proxy
go run main.go -user=hbdev -domain=hbdev-PC -password=123456
```

start client

```shell
go run main.go
```
