
build-backend:
	go clean && GOOS=darwin GOARCH=arm64 go build -o backend  -ldflags="-X main.BuildStamp=`date +%Y-%m-%d.%H:%M:%S`" backend.go
