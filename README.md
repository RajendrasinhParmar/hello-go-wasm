### Hello Go Wasm
This is an example of creating webassembly using go language.
It also contains server that server the static files.

To execute and check the implementation follow the below steps.


```shell
cd ./cmd/wasm
GOOS=js GOARCH=wasm go build -o ../../assets/json.wasm
cd ../server
go run main.go
```

Now open website using `localhost:9090` the bomb and disabled it.