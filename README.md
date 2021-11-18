### embed

This package converts any file into Go source code(bytes) without any package
simple and clean


### Installation

To install the command line program, use the following:

    go get -u github.com/jaslac/go-embed/...


### Usage

Convert files to embed.go

    $ go-embed x.txt x.exe x.html

### Output

$ go-embed main.go README.md

```go
// Code generated by go-embed.
package main

// _mainGo from main.go
var _mainGo = []byte("\x70\x61\x63\x6b...")

// _readmeMd from README.md
var _readmeMd = []byte("\x23\x23\x23\x20...")
```