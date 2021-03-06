# fnrun

[![GoDoc](https://godoc.org/github.com/tessellator/fnrun?status.svg)](https://godoc.org/github.com/tessellator/fnrun)
[![Go Report Card](https://goreportcard.com/badge/tessellator/fnrun)](https://goreportcard.com/report/tessellator/fnrun)
[![Releases](https://img.shields.io/github/v/tag/tessellator/fnrun?include_prereleases&sort=semver)](https://github.com/tessellator/fnrun/releases)
[![LICENSE](https://img.shields.io/github/license/tessellator/fnrun.svg)](https://github.com/tessellator/fnrun/blob/master/LICENSE)

`fnrun` is a library that provides utilities for building and executing
function runners with isolation.

This library provides an implementation that can be used to interface with CLI
applications using the [fnrun-proto](https://github.com/tessellator/fnrun-proto)
protocol buffers to stream data over stdin and stdout to the CLI application.
