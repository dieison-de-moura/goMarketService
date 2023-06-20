## Configurações

- Verifique se você tem golang instalado:
```go version```
- Output esperado:
```go version go1.20.5 linux/amd64```
- Caso não tenha, verifique o manual de instalação: https://go.dev/doc/install

- Inicie os containers docker:
```docker compose up -d```
- OBS: Seu arquivo hosts precisa conter: **127.0.0.1 host.docker.internal**

- Execute o programa em go:
```go run cmd/trade/main.go```
