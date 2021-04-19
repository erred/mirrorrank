# mirrorrank

Arch Linux mirrorlist ranker

[![pkg.go.dev](http://img.shields.io/badge/godoc-reference-blue.svg?style=flat-square)](https://pkg.go.dev/go.seankhliao.com/mirrorrank)
![Version](https://img.shields.io/github/v/tag/seankhliao/mirrorrank?sort=semver&style=flat-square)
[![License](https://img.shields.io/github/license/seankhliao/mirrorrank.svg?style=flat-square)](LICENSE)

## build / install

```sh
go install go.seankhliao.com/mirrorrank@latest
```

## usage

```sh
sudo mirrorrank
```

## config

```txt
Usage of mirrorrank:
  -4        limit to IPv4
  -6        limit to IPv6
  -c value
            limit to countries (repeatable)
  -e value
            exclude string
  -f string
            mirrorlist to use instead of from archlinux.org/mirrorlist/
  -l int
            limit output (default 5)
  -p int
            parallel downloads (default 10)
  -s string
            output file location (default "/etc/pacman.d/mirrorlist")
```
