# Summary

- **Alfred Workflow**
  - [Switch DNS](#switch-dns) This is an useful workflow for switch your DNS.
- **CTF & Pentest**
  - [Hashpow](#hashpow) Fuck the hash proof of work for ctfer
  - [Reverse Shell](#reverse-shell) Easy to remember reverse shell.
  - [JWTTool](#jwttool) A jwt tool with Print/Crack/Modify.
  - [GitHack](#githack) A `.git` folder disclosure exploit.
  - [Gopher](#gopher) A tool for generate Gopher exp

# Tools List

## Gopher

~~[Source Code](#)~~

A tool for generate Gopher exp

[![](https://img.shields.io/badge/Download%208M-Qiniu-blue)](http://virzz-img.dongzt.cn/tools/ctf/gopher.zip)
[![](https://img.shields.io/badge/Download%208M-Github-blue)](https://github.com/virzz/tools.virzz.com/releases/tag/gopher1.1)

**File List:**

- SHA256.txt
- gopher-darwin-amd64
- gopher-linux-386
- gopher-linux-amd64
- gopher-windows-386.exe
- gopher-windows-amd64.exe

## GitHack

~~[Source Code](#)~~

A Git source leak exploit tool that restores the entire Git repository, including data from stash, for white-box auditing and analysis of developers' mind

[![](https://img.shields.io/badge/Download%2018M-Qiniu-blue)](http://virzz-img.dongzt.cn/tools/ctf/githack.zip)
[![](https://img.shields.io/badge/Download%2018M-Github-blue)](https://github.com/virzz/tools.virzz.com/releases/tag/githack1.0)

**File List:**

- SHA256.txt
- githack-darwin-386
- githack-darwin-amd64
- githack-linux-386
- githack-linux-amd64
- githack-windows-386.exe
- githack-windows-amd64.exe

## JWTTool

~~[Source Code](#)~~

A jwt tool with Print/Crack/Modify

[![](https://img.shields.io/badge/Download%2010M-Qiniu-blue)](http://virzz-img.dongzt.cn/tools/ctf/jwttool.zip)
[![](https://img.shields.io/badge/Download%2010M-Github-blue)](https://github.com/virzz/tools.virzz.com/releases/tag/jwt1.0)

**File List:**

- SHA256.txt
- jwttool-darwin-386
- jwttool-darwin-amd64
- jwttool-linux-386
- jwttool-linux-amd64
- jwttool-windows-386.exe
- jwttool-windows-amd64.exe

## Reverse Shell

[Source Code](https://github.com/virink/reverse-shell)

Easy to remember reverse shell that should work on most Unix-like systems.

[https://resh.now.sh/](https://resh.now.sh/)

Example: [https://resh.now.sh/localhost:1337](https://resh.now.sh/localhost:1337)

*Luke Childs didn't accept PR#15, so I I made a new one*

**Reference**
> https://github.com/Lz1y/reverse-shell
> > https://github.com/lukechilds/reverse-shell

## Switch DNS

[![](https://img.shields.io/badge/Download%201.8M-Qiniu-blue)](http://virzz-img.dongzt.cn/tools/alfredworkflow/SwitchDNS.alfredworkflow)


This is an useful workflow for switch your DNS.

Default DNS:

| Name   | Server IP                       |
| ------ | ------------------------------- |
| Google | 8.8.8.8,8.8.4.4                 |
| Aliyun | 223.5.5.5,223.6.6.6             |
| 114    | 114.114.114.114,114.114.115.115 |


You can add your custom DNS Server for your work!

## Hashpow

[Source Code](https://github.com/virink/hashpow)

[![](https://img.shields.io/badge/Download%2023M-Qiniu-blue)](http://virzz-img.dongzt.cn/tools/ctf/hashpow.tar.gz)

[https://hashpow.now.sh/](https://hashpow.now.sh/)

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