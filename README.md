go build -tags netgo -ldflags '-s -w' -o app
go build -tags=jsoniter -o app .