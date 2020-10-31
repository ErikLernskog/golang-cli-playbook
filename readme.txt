# test
go test -v ./module*

m1
go env > module1.txt
go env -json > module1.json

m2
go fmt module2_hello.go
gofmt -w module2_code.go

m3
go get github.com/nathan-osman/go-sunrise
cp go.mod module3/go.mod.copy

m4
go get github.com/codemodus/kace

m5
goimports -w module5_code.go