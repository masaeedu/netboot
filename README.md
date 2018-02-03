# Netboot, packages and utilities for network booting

[![license](https://img.shields.io/github/license/google/netboot.svg?maxAge=2592000)](https://github.com/google/netboot/blob/master/LICENSE) [![Travis](https://img.shields.io/travis/google/netboot.svg?maxAge=2592000)](https://travis-ci.org/google/netboot)  [![api](https://img.shields.io/badge/api-unstable-red.svg)](https://godoc.org/github.com/masaeedu/netboot)

This repository contains Go implementations of network protocols used
in booting machines over the network, as well as software that make
use of those implementations.

This is not an official Google project.

The canonical import path for Go packages in this repository is `github.com/masaeedu/netboot`.

## Libraries

- [pcap](https://godoc.org/github.com/masaeedu/netboot/pcap): Pure Go implementation of reading and writing pcap files.
- [dhcp4](https://godoc.org/github.com/masaeedu/netboot/dhcp4): DHCPv4 library providing the low-level bits of a DHCP client/server (packet marshaling, RFC-compliant packet transmission semantics).
- [tftp](https://godoc.org/github.com/masaeedu/netboot/tftp): Read-only TFTP server implementation.
- [pixiecore](https://godoc.org/github.com/masaeedu/netboot/pixiecore): the functionality of Pixiecore (see below), in library form. Every stability warning in this repository applies double for this package.

## Programs

- [Pixiecore](https://github.com/google/netboot/tree/master/pixiecore): an all-in-one tool for easy netbooting.
