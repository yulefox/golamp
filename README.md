# Lamp

[![GoDoc][I1]][L1] [![License][I2]][L2] [![Build Status][I3]][L3] [![Coverage Status][I4]][L4]

[I1]: http://img.shields.io/badge/go-documentation-blue.svg?style=flat-square
[L1]: http://godoc.org/github.com/yulefox/lamp
[I2]: http://img.shields.io/badge/license-MIT-blue.svg?style=flat-square
[L2]: LICENSE
[I3]: https://img.shields.io/travis/yulefox/lamp.svg?style=flat-square
[L3]: https://travis-ci.org/yulefox/lamp
[I4]: https://img.shields.io/codecov/c/github/yulefox/lamp.svg?style=flat-square
[L4]: https://codecov.io/gh/yulefox/lamp

A Go microservice frame based on NSQ.

## Stack

- [Go](https://golang.org)
- [Glide](https://glide.sh)
- [NSQ](http://nsq.io)
- [Echo](http://github.com/labstack/echo)

## Install

```sh
glide update
```

## Test

```sh
./test.sh
```

## Usage

```go
lamp.On(s)
```

## License

[MIT](LICENSE)
