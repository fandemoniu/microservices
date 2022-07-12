proto:
	protoc --go_out=. --go_opt=paths=source_relative \                                                      
    --go-grpc_out=. --go-grpc_opt=paths=source_relative \
    pkg/pb/product.proto

server:
	go run cmd/main.go