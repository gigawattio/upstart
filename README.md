# upstart

[![Documentation](https://godoc.org/github.com/gigawattio/oslib?status.svg)](https://godoc.org/github.com/gigawattio/oslib)
[![Build Status](https://travis-ci.org/gigawattio/oslib.svg?branch=master)](https://travis-ci.org/gigawattio/oslib)
[![Report Card](https://goreportcard.com/badge/github.com/gigawattio/oslib)](https://goreportcard.com/report/github.com/gigawattio/oslib)

### About

Go (golang) package which provides turn-key [Ubuntu Upstart](http://upstart.ubuntu.com/) system service management integration for your application!

Created by [Jay Taylor](https://jaytaylor.com/) and used by [Gigawatt](https://gigawatt.io/).

### Requirements

* Go version 1.3 or newer

### Running the test suite

    go test ./...

## TODO

* [ ] Fix upstart serviceifier to pickup and preserve flags.
* [ ] Update upstart serviceifier refuse to install as root?

#### License

Permissive MIT license, see the [LICENSE](LICENSE) file for more information.
