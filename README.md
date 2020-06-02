# Virink's Tools List

## Summary

- **Alfred Workflow**
  - [Switch DNS](#switch-dns) This is an useful workflow for switch your DNS.
- **CTF & Pentest**
  - [Hashpow](#hashpow) Fuck the hash proof of work for ctfer
  - [Reverse Shell](#reverse-shell) Easy to remember reverse shell.

## Tools List

### Reverse Shell

[Source Code](https://github.com/virink/reverse-shell)

Easy to remember reverse shell that should work on most Unix-like systems.

[https://resh.now.sh/](https://resh.now.sh/)

Example: [https://resh.now.sh/localhost:1337](https://resh.now.sh/localhost:1337)

*Luke Childs didn't accept PR#15, so I I made a new one*

**Reference**
> https://github.com/Lz1y/reverse-shell
> > https://github.com/lukechilds/reverse-shell

### Switch DNS

[Download 1.8 M](http://virzz-img.dongzt.cn/tools/alfredworkflow/SwitchDNS.alfredworkflow)

This is an useful workflow for switch your DNS.

Default DNS:

| Name   | Server IP                       |
| ------ | ------------------------------- |
| Google | 8.8.8.8,8.8.4.4                 |
| Aliyun | 223.5.5.5,223.6.6.6             |
| 114    | 114.114.114.114,114.114.115.115 |


You can add your custom DNS Server for your work!

### Hashpow

[Source Code](https://github.com/virzz/hashpow)

[Download 23M](http://virzz-img.dongzt.cn/tools/ctf/hashpow.tar.gz)

Fuck the hash proof of work for ctfer

**File List:**

- SHA256.txt
- SHA256_Package.txt
- hashpow-darwin-386
- hashpow-darwin-amd64
- hashpow-linux-386
- hashpow-linux-amd64
- hashpow-windows-386.exe
- hashpow-windows-amd64.exe

I packed by upx, if you want to unpack, just run `upx -d *`