### embed

Converts any file into Go source code(bytes) without any package, simple and clean


### Usage

Convert main.go README.md to embed.go

    $ go-embed main embed.go main.go README.md

Output

```go
// Code generated by go-embed.
package main

// _mainGo from main.go
var _mainGo = []byte("\x70\x61\x63\x6b...")

// _readmeMd from README.md
var _readmeMd = []byte("\x23\x23\x23\x20...")
```