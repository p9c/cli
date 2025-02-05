cli
===

[![Build Status](https://travis-ci.org/p9c/cli.svg?branch=master)](https://travis-ci.org/p9c/cli)
[![Windows Build Status](https://ci.appveyor.com/api/projects/status/rtgk5xufi932pb2v?svg=true)](https://ci.appveyor.com/project/p9c/cli)

[![GoDoc](https://godoc.org/github.com/p9c/cli?status.svg)](https://godoc.org/github.com/p9c/cli)
[![codebeat](https://codebeat.co/badges/0a8f30aa-f975-404b-b878-5fab3ae1cc5f)](https://codebeat.co/projects/github-com-urfave-cli)
[![Go Report Card](https://goreportcard.com/badge/p9c/cli)](https://goreportcard.com/report/p9c/cli)
[![codecov](https://codecov.io/gh/p9c/cli/branch/master/graph/badge.svg)](https://codecov.io/gh/p9c/cli)

cli is a simple, fast, and fun package for building command line apps in Go. The
goal is to enable developers to write fast and distributable command line
applications in an expressive way.

## Usage Documentation

Usage documentation exists for each major version

- `v1` - [./docs/v1/manual.md](./docs/v1/manual.md)
- `v2` - 🚧 documentation for `v2` is WIP 🚧

## Installation

Make sure you have a working Go environment.  Go version 1.10+ is supported.  [See
the install instructions for Go](http://golang.org/doc/install.html).

### GOPATH

Make sure your `PATH` includes the `$GOPATH/bin` directory so your commands can
be easily used:
```
export PATH=$PATH:$GOPATH/bin
```

### Supported platforms

cli is tested against multiple versions of Go on Linux, and against the latest
released version of Go on OS X and Windows.  For full details, see
[`./.travis.yml`](./.travis.yml) and [`./appveyor.yml`](./appveyor.yml).

### Using `v1` releases

```
$ go get github.com/p9c/cli
```

```go
...
import (
  "github.com/p9c/cli"
)
...
```

### Using `v2` releases

**Warning**: `v2` is in a pre-release state.

```
$ go get github.com/p9c/cli.v2
```

```go
...
import (
  "github.com/p9c/cli.v2" // imports as package "cli"
)
...
```
