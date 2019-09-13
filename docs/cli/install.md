---
layout: default
title: Installation
parent: CLI
nav_order: 1
---

# Installation
{: .no_toc }

---

## Precompiled binary

Get the latest precompiled binaries for Linux and Mac Os X from the [download page](https://github.com/Standardized-Objects/standardized/releases)

---

## Build from source

### Clone
```bash
$ git clone git@github.com:Standardized-Objects/standardized.git $GOPATH/src/standardized
```
### Install deps
```bash
$ cd $GOPATH/src/standardized
$ dep ensure
```
### Build & Install in $GOBIN
```bash
$ cd $GOPATH/src/standardized
$ go install
```
