.PHONY: deps clean build

deps:
	go get github.com/tencentyun/scf-go-lib/cloudfunction

clean: 
	rm -rf ./hello_world/hello_world
	
build:
	GOOS=linux GOARCH=amd64 go build -o hello_world/hello_world ./hello_world
