# go_environment

### Environment variable / Shows go environment variables
```bash 
go env
```
##### Attention to the variables:
* GOPATH="/Users/joaocarvalho/go" (Main GO Folder, with bin and pkg)
* GOROOT="/usr/local/go" (Golang installation location)

### Create a module, project go
```bash
  go mod init github.com/joaokvalho/namepackage
```

### Run and compile the application
```bash
  go run file.go
```

### Build the build and compile the application
```bash
  go build file.go
```

### Build the target Operating System
#### Example:
```bash
GOOS=windows go build main.go // Compile the application for windows
```

### Installation of external libs
```bash
  go get -u github.com/lib/pq
```

### Check for invalid codes
```bash
  go vet
```

### Update dependency package in project
```bash
  go mod tidy
```

### Show structure vendor in project
```bash
  go mod vendor
```
