{{.Name}}
====

[![GitHub release](http://img.shields.io/github/release/{{.User}}/{{.Name}}.svg?style=flat-square)][release]
[![Wercker](http://img.shields.io/wercker/ci/54330318b4ce963d50020750.svg?style=flat-square)][wercker]
[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)][license]
[![Go Documentation](http://img.shields.io/badge/go-documentation-blue.svg?style=flat-square)][godocs]

[release]: https://github.com/{{.User}}/{{.Name}}/releases
[license]: https://github.com/{{.User}}/{{.Name}}/blob/master/LICENSE
[godocs]: http://godoc.org/github.com/{{.User}}/{{.Name}}


## Description

{{.Description}}

## Demo

{{.Demo}}

## Usage

{{.Usage}}

## Install

To install, use `go get`:

```bash
$ go get -u github.com/{{.User}}/{{.Name}}
```

## Contribution

1. Fork ([https://github.com/{{.User}}/{{.Name}}/fork](https://github.com/{{.User}}/{{.Name}}/fork))
1. Create a feature branch
1. Commit your changes
1. Rebase your local changes against the master branch
1. Run test suite with the `go test ./...` command and confirm that it passes
1. Run `gofmt -s`
1. Create new Pull Request

## Author

[{{.User}}](https://github.com/{{.User}})
