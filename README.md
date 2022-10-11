# Awesome `io_uring` <a name="introduction"></a>
Delightful `io_uring` packages and resources


# Table of contents

1. [Introduction](#introduction)
2. [Tutorials](#Tutorials)
4. [Libraries](#Tutorials)
   - [C](#C) 
   - [Rust](#Rust)
   - [Golang](#Golang)
5. [Projects using io_uring](#projects)
6. [Articles](#Articles)
7. [Other notable resources](#other)


## Tutorials
Tutorials about io_uring

- [Lord of the io_uring](https://unixism.net/loti/): Amazing collection of tutorials with deep explanations, 
unfortunately not updated often

## Libraries 
Libraries for using `io_uring`

### C

- [liburing](https://github.com/axboe/liburing): Helper to interact with the kernel `io_uring` interface
- [xnvme](https://xnvme.io/): NVMe library with `io_uring` support
- [SPDK](https://spdk.io/): Intel library focused on performant io, with `io_uring` support

### Rust

- [tokio-uring](https://github.com/tokio-rs/tokio-uring): An `io_uring` backend for tokio
- [rio](https://github.com/spacejam/rio): Pure rust `io_uring` library, unfortunately unmaintained 

### Golang

- [gouring](https://github.com/ii64/gouring): Amazing `io_uring` library in pure golang

## Projects <a name="projects"></a>
Projects using io_uring

- [Glommio](https://github.com/DataDog/glommio)
- [Monoio](https://github.com/bytedance/monoio)

## Articles
Articles about io_uring

## Other notable resources <a name="other"></a>
Other resources about io_uring

- [IRC channel](https://webchat.oftc.net/?nick=amazingnickname&channels=%23io_uring&uio=d4): 
discussions about `io_uring`, you can find the archives [here](https://oftc.irclog.whitequark.org/io_uring/)
- [Mailing list](https://lore.kernel.org/io-uring/): The official dev mailing list of `io_uring`