# Redsync-Radix

[![Build Status](https://travis-ci.org/go-redsync/redsync.svg?branch=master)](https://travis-ci.org/go-redsync/redsync)

Redsync-Radix provides a Redis-based distributed mutual exclusion lock implementation for Go by using [radix](https://github.com/mediocregopher/radix) as described in [this post](http://redis.io/topics/distlock). A reference library (by [antirez](https://github.com/antirez)) for Ruby is available at [github.com/antirez/redlock-rb](https://github.com/antirez/redlock-rb).

## Installation

Install Redsync-Radix using the go get command:

    $ go get github.com/kayalardanmehmet/redsync-radix

The only dependencies are the Go distribution and [radix](https://github.com/mediocregopher/radix).

## Documentation

- [Reference](https://godoc.org/gopkg.in/redsync.v1)

## Contributing

Contributions are welcome.

## License

Redsync is available under the [BSD (3-Clause) License](https://opensource.org/licenses/BSD-3-Clause).

## Disclaimer

This code implements an algorithm which is currently a proposal, it was not formally analyzed. Make sure to understand how it works before using it in production environments.
