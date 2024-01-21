# Go Made Easy

## Installing Go
https://go.dev/doc/install

#### Create GOPATH environment variable
Go to Control Panel -> System And Security -> System -> Advanced System Settings -> Environment Variables.
Set the following environment variables for the `user` PATH.
```
GOPATH=D:\go
```
#### Create GOPATH directories
```
mkdir -p $GOPATH/src $GOPATH/pkg $GOPATH/bin
```
In Go, the `src`, `pkg`, and `bin` directories are part of the GOPATH workspace structure. This structure is used to organize Go projects and their corresponding source code, compiled packages, and executable binaries.

- src Directory

The src directory is where your Go source code resides. Inside src, you organize your code into packages based on their import paths.
For example, if your project is hosted on GitHub at github.com/yourusername/yourproject, your source code would be located in the src/github.com/yourusername/yourproject directory. Each package typically has its own subdirectory under src. For example, the main package of your project might be in src/github.com/yourusername/yourproject/cmd/main.

- pkg Directory
  
The pkg directory stores compiled package object files (.a files) generated during the build process.
These package object files are intermediate artifacts representing precompiled versions of your packages. They are stored in a directory structure that reflects the target architecture and operating system.
This directory is created to speed up the build process by avoiding the recompilation of unchanged packages. It helps in achieving parallel builds and reduces rebuild times.

- bin Directory
  
The bin directory is where the compiled executable binaries are placed after the `go install` command is executed.
When you build a Go program, the resulting executable is placed in the bin directory, with its name being the same as the last element of the import path.
For example, if your project is located at github.com/yourusername/yourproject and you run go install, the resulting executable will be in the bin directory as yourproject.

#### Add GOPATH/bin to your path
Go to Control Panel -> System And Security -> System -> Advanced System Settings -> Environment Variables.
Add the following directory to the `user` PATH.
```
D:\go\bin
```
Any commands that you compile using the go install command will be saved to the $GOPATH/bin directory. Putting this directory on the path makes it easy to run commands.

## Learning Go
https://go.dev/learn/
