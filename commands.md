# All Go Commands

## Basics
Get help
```sh
go hel9
```
Get Go version
```sh
go version
```
Print Go environment information
```sh
go env
```
Modules
```sh
$ go help
Go is a tool for managing Go source code.

Usage:

    go command [arguments]

The commands are:

build       compile packages and dependencies
get         download and install packages and dependencies
install     compile and install packages and dependencies
test        test packages
```
```sh
go get github.com/.....
go install github.com/.....
```
The `go install` command builds a binary and places it in `$GOPATH/bin/NAME`
