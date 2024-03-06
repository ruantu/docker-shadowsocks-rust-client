# Docker-Shadowsocks-Rust-Client
Simple Docker Shadowsocks-Rust client image based on Alpine.

## Introductions
This project aims to run commonly used NAS software in Docker.

## How to build

### Build command
`docker build -t ruantu/shadowsocks-rust-client:latest .`

## How to use

### Mapping port
- HTTP Proxy Port: 4001 TCP
- Socks5 Proxy Port: 4002 TCP/UDP

### Mounting volumes
- Configuration file: `/etc/shadowsocks-rust/config.json`  

### Software packages
- [shadowsocks-rust-ssurl](https://pkgs.alpinelinux.org/packages?name=shadowsocks-rust-ssurl&branch=edge&repo=&arch=&maintainer=)
- [shadowsocks-rust-sslocal](https://pkgs.alpinelinux.org/packages?name=shadowsocks-rust-sslocal&branch=edge&repo=&arch=&maintainer=)
- [shadowsocks-rust-ssservice](https://pkgs.alpinelinux.org/packages?name=shadowsocks-rust-ssservice&branch=edge&repo=&arch=&maintainer=)
