git clone https://github.com/MoeinGhbh/golang-docker.git

$ export GOFLAGS=-mod=vendor
$ export GO111MODULE=on
$ go mod init github.com/YOUR_GITHUB_USER/YOUR_REPOSITORY_NAME 
# (example: go mod init github.com/tomfern/go-web-docker)


$ go mod download
$ go mod vendor
$ go mod verify