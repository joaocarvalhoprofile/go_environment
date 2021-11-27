# go_environment

Environment variable
```bash 
go env
```

Create project package
```
  go mod init github.com/joaokvalho/namepackage
```

Instal package external
```
  go get -u package_name
```

Update dependency package in project
```
  go mod tidy
```

Show structure vendor in project
```
  go mod vendor
```

Execute:
```
  go run filename.go
```

Create build:
```
  go build filename.go
```

Create build for OS target:
```
  GOOS=windows go build filename.go
```
