# Summary

- **All in Virzz**
  - [God](#god) The Cyber Swiss Army Knife for terminal.
  - [ ] ~~[Platform](#platform) The Cyber Swiss Army Knife for platform.~~
- **Alfred Workflow**
  - [Switch DNS](#switch-dns) This is an useful workflow for switch your DNS.
- **CTF & Pentest**
  - [JWTTool](#jwttool) A jwt tool with Print/Crack/Modify.
  - [GitHack](#githack) A `.git` folder disclosure exploit.
  - [Gopher](#gopher) A tool for generate Gopher exp
  - [Parser](#parser) A tool for parse some files
  - [Hashpow](#hashpow) Fuck the hash proof of work for ctfer
  - [Reverse Shell](#reverse-shell) Easy to remember reverse shell.

# Tools List

## God

[Source Code](https://github.com/virzz/virzz)

The Cyber Swiss Army Knife for terminal.

### Install

- `brew install virzz/virzz/god`
- Download from [GitHub](https://github.com/virzz/virzz/releases/latest)

## Parser

[Source Code](https://github.com/virzz/virzz/tree/master/modules/misc/parser)

A tool for parse some files

[![](https://img.shields.io/badge/Download%2015.42M-Qiniu-blue)](http://virzz-img.ctfhub.com/tools/ctf/parser.zip)

## Gopher

[Source Code](https://github.com/virzz/virzz/tree/master/modules/web/gopher)

A tool for generate Gopher exp

[![](https://img.shields.io/badge/Download%2010.7M-Qiniu-blue)](http://virzz-img.ctfhub.com/tools/ctf/gopher.zip)


## GitHack

[Source Code](https://github.com/virzz/virzz/tree/master/modules/web/githack)

A Git source leak exploit tool that restores the entire Git repository, including data from stash, for white-box auditing and analysis of developers' mind

[![](https://img.shields.io/badge/Download%2016M-Qiniu-blue)](http://virzz-img.ctfhub.com/tools/ctf/githack.zip)


## JWTTool

[Source Code](https://github.com/virzz/virzz/tree/master/modules/web/jwttool)

A jwt tool with Print/Crack/Modify

[![](https://img.shields.io/badge/Download%209.88M-Qiniu-blue)](http://virzz-img.ctfhub.com/tools/ctf/jwttool.zip)


## Reverse Shell

[Source Code](https://github.com/virzz/reverse-shell)

Easy to remember reverse shell that should work on most Unix-like systems.

- [https://resh.now.sh/](https://resh.now.sh/)
- [https://resh.vercel.app/](https://resh.vercel.app/)

Example: [https://resh.now.sh/localhost:1337](https://resh.now.sh/localhost:1337)

*Luke Childs didn't accept PR#15, so I made a new one*

**Reference**
> https://github.com/Lz1y/reverse-shell
> > https://github.com/lukechilds/reverse-shell

## Switch DNS

[![](https://img.shields.io/badge/Download%201.8M-Qiniu-blue)](http://virzz-img.ctfhub.com/tools/alfredworkflow/SwitchDNS.alfredworkflow)


This is an useful workflow for switch your DNS.

Default DNS:

| Name   | Server IP                       |
| ------ | ------------------------------- |
| Google | 8.8.8.8,8.8.4.4                 |
| Aliyun | 223.5.5.5,223.6.6.6             |
| 114    | 114.114.114.114,114.114.115.115 |


You can add your custom DNS Server for your work!

## Hashpow

Fuck the hash proof of work for ctfer

### Newer (Rebuild Just Cli)

[Source Code](https://github.com/virzz/virzz/tree/master/modules/crypto/hashpow)

[![](https://img.shields.io/badge/Download%207.72M-Qiniu-blue)](http://virzz-img.ctfhub.com/tools/ctf/hashpow.zip)

### Older

[Source Code](https://github.com/virzz/hashpow)

[https://hashpow.vercel.app/](https://hashpow.vercel.app/)

Usage: 
```
Usage:
request: /?c=[code]&t=[hash type]&pf=[prefix string]&sf=[suffix sstring]&p=[pos]&r=[true]
Params:
- c [string] Code (**require**)
- t [string] hash Type : md5 sha1 (**require**)
- p [int] starting Position of hash
- pf [string] text Prefix
- sf [string] text Suffix
- r [boolean] Raw resopnse
eg: /?c=abcdef&t=md5
    /?c=abcdef&t=md5&pf=v&sf=k&p=6
```


