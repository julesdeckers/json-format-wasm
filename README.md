# Compile
```bash
cd cmd/wasm
GOOS=js GOARCH=wasm go build -o ../../assets/json.wasm
```

# Run
```bash
cd cmd/server
go run main.go
```

(link)[https://golangbot.com/webassembly-using-go/]