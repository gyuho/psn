## linux-inspect

[![Go Report Card](https://goreportcard.com/badge/github.com/gyuho/linux-inspect?style=flat-square)](https://goreportcard.com/report/github.com/gyuho/linux-inspect)
[![Build Status](https://img.shields.io/travis/gyuho/linux-inspect.svg?style=flat-square)](https://travis-ci.org/gyuho/linux-inspect)
[![Build Status](https://semaphoreci.com/api/v1/gyuho/linux-inspect/branches/master/shields_badge.svg)](https://semaphoreci.com/gyuho/linux-inspect)
[![Godoc](https://img.shields.io/badge/godoc-documentation-blue.svg?style=flat-square)](https://godoc.org/github.com/gyuho/linux-inspect)

linux-inspect implements various Linux inspecting utilities.

```
go get -v github.com/gyuho/linux-inspect/cmd/linux-inspect
```

```
Usage:
  linux-inspect [command]

Available Commands:
  ds          Inspects '/proc/diskstats'
  ns          Inspects '/proc/net/dev'
  ps          Inspects '/proc/$PID/status', 'top' command output
  ss          Inspects '/proc/net/tcp,tcp6'
```
