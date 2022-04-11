# Compile
cd cmd/wasm
GOOS=js GOARCH=wasm go build -o ../../assets/json.wasm

# Run
cd cmd/server
go run main.go

(link)[https://golangbot.com/webassembly-using-go/]