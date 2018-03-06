## Quickstart Guide for Unix (Mac)

### Installation
[installation](https://golang.org/doc/install)
 - installed into /usr/local/go/bin
 - run `/usr/local/go/bin/go version` from the cmd line
 - go cmd should be added to path but if not prepend to path manually
 - add `export PATH=/usr/local/go/bin/:$PATH` to ~/.bash_profile


### GO workspace path
If no GOPATH env var is set, it is assumed to be $HOME/go
 - edit ~/.bash_profile       
 - export GOPATH=$HOME/go 
 - source .bash_profile

export GOPATH=$(go env GOPATH)



### setting up sublime text editor with GO
`git clone https://github.com/DisposaBoy/GoSublime`  inside of
/Users/[user]/Library/Application Support/Sublime Text 2/Packages



### browser playground for code
https://play.golang.org/


### building
`go build` inside of a directory will build an executable with the name of that directory

### installing
`go install github.com/user/hello`  will install the executable into the GOPATH/bin directory.
(This assumes that the GOPATH has been setup correctly, as in [the official docs](https://golang.org/doc/code.html))



