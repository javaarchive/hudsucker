# hudsucker

[![crates.io](https://img.shields.io/crates/v/hudsucker)](https://crates.io/crates/hudsucker)
[![docs.rs](https://docs.rs/hudsucker/badge.svg)](https://docs.rs/hudsucker)
[![Build](https://github.com/omjadas/hudsucker/actions/workflows/build.yml/badge.svg)](https://github.com/omjadas/hudsucker/actions/workflows/build.yml)

Hudsucker is a MITM HTTP/S proxy written in Rust that allows you to:

- Modify HTTP/S requests
- Modify HTTP/S responses
- Modify websocket messages

## Features

- `full`: Enables all features.
- `http2`: Enables HTTP/2 support.
- `openssl-certs`: Enables `OpensslAuthority`.
- `rcgen-certs`: Enables `RcgenAuthority` (enabled by default).

## Usage

For usage, refer to the [provided examples](https://github.com/omjadas/hudsucker/tree/main/examples).
