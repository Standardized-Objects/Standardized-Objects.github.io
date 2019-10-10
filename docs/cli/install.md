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

Get the latest precompiled binaries from the [download page](https://github.com/Standardized-Objects/standardized/releases)

---

## Build from source

### Clone

    git clone https://github.com/Standardized-Objects/standardized.git $GOPATH/src/standardized

### Install deps

    cd $GOPATH/src/standardized
    dep ensure

### Build & Install in $GOBIN

    cd $GOPATH/src/standardized
    go build -ldflags="-s -w" .
    upx -9 standardized
    mv standardized $GOBIN/
