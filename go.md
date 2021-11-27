# go_environment

### Environment variable / Shows go environment variables
```bash 
go env
```
##### Attention to the variables:
* GOPATH="/Users/joaocarvalho/go" (Main GO Folder, with bin and pkg)
* GOROOT="/usr/local/go" (Golang installation location)


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

### Create a module, project go
```bash
  go mod init github.com/joaokvalho/namepackage
```

### Installation of external libs
```bash
  go get -u github.com/lib/pq
```

### Build the build and compile the application
```bash
  go build file.go
```

### Run and compile the application
```bash
  go run file.go
```

GOOS=windows // Operating System Variables Arrow
Example:
GOOS=windows go build main.go // Compile the application for windows



### Create project package
```bash
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
