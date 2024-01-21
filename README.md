# Go Made Easy

## Installing Go
https://go.dev/doc/install

### Create GOPATH environment variable
Go to Control Panel -> System And Security -> System -> Advanced System Settings -> Environment Variables.

Set the following environment variables for the user:
```
GOPATH=D:\go
```
### Create GOPATH directories
```
mkdir -p $GOPATH/src $GOPATH/pkg $GOPATH/bin
```
### Add GOPATH/bin to your path
Go to Control Panel -> System And Security -> System -> Advanced System Settings -> Environment Variables.
Add the following directory to the user PATH
```
D:\go\bin
```
Any commands that you compile using the go install command will be saved to the $GOPATH/bin directory. Putting this directory on the path makes it easy to run commands.

## Learning Go
https://go.dev/learn/
