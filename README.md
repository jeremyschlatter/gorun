# gorun

This is a fork of Gustavo Niemeyer's gorun. It lets you use a shebang line to run Go source files:

    $ cat hello.go
    #!/usr/bin/env gorun
    
    package main
    
    import "fmt"
    
    func main() {
        fmt.Println("Hello world!")
    }
    $ chmod +x hello.go
    $ ./hello.go
    Hello world!

More info here: [https://wiki.ubuntu.com/gorun](https://wiki.ubuntu.com/gorun)

Forked from: [https://launchpad.net/gorun](https://launchpad.net/gorun)

## Installing

    go get github.com/jeremyschlatter/gorun
