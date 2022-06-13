# docker-template-go
Goのdockerテンプレート。

# イメージのビルド
```bash
make build
```

## go.mod
go.modを作成する。`example/hello`の部分は適宜変更すること。
```bash
docker-compose run --rm app go mod init example/hello
```
