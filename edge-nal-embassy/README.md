# edge-nal-embassy

[![CI](https://github.com/ivmarkov/edge-net/actions/workflows/ci.yml/badge.svg)](https://github.com/ivmarkov/edge-net/actions/workflows/ci.yml)
![crates.io](https://img.shields.io/crates/v/edge-net.svg)
[![Documentation](https://docs.rs/edge-net/badge.svg)](https://docs.rs/edge-net)

A bare-metal implementation of `edge-nal` based on the `embassy-net`(https://crates.io/crates/embassy-net) crate - the netowkring stack of the Embassy echosystem.

Implemented traits from `edge-net`:
* TCP: all
* UDP: all except `UdpConnect`
* Raw sockets: not implemented yet, as `embassy-net` does not expose raw sockets

TODO: Needs testing!