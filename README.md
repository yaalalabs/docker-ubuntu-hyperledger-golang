# ubuntu-hyperledger-golang

This repository contains the build specification for [yaalalabs/ubuntu-hyperledger-golang](https://hub.docker.com/r/yaalalabs/ubuntu-hyperledger-golang) Docker image.

This image is intended for development and testing of Hyperledger Fabric chaincode on Ubuntu using the Go programming language.

**Base Image**
* ubuntu:latest

**Ubuntu Packages**
* git
* golang

**Go Packages**
* github.com/hyperledger/fabric/core/chaincode/shim
* github.com/hyperledger/fabric/protos/peer
* github.com/pkg/errors
* github.com/stretchr/testify/assert
* github.com/tebeka/go2xunit
