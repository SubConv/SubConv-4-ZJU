# Subscription Converter
English | [Chinese](README_CN.md)  
![license](https://img.shields.io/github/license/SubConv/SubConv-4-ZJU) ![last commit](https://img.shields.io/github/last-commit/SubConv/SubConv-4-ZJU)  
This is a fork of [SubConv](https://github.com/SubConv/SubConv), but I can't fork my own project, so I manually created a repository.  

## Features
- Support Clash config and V2ray format base64 links (i.e. the original subscription does not have to be Clash)  
- A Web-UI (thanks to [@Musanico](https://github.com/musanico))  
- Rules based on ACL (including ZJU special rules)  
- Nodes auto update based on proxy-provider  
- Support multiple airpots  
- Display remaining traffic and total traffic (only useful when you use a single airport, requires your airport and Clash to support it at the same time, Clash for Windows, Clash Verge, Stash, Clash Meta for Android, etc. are known to support it)  
- Implement the api of subscription conversion to proxy-provider (normal people won't use it)  
- Support configuration file `config.py`, where you can customize rules and other things (maybe I will write a subconverter configuration to this project in the future)  

## Docs
[docs](https://subconv.is-sb.com) (both Chinese and English, but machine translated)  

## P.S
**If you're using the Clash Core from Dreamacro, you need v1.15.0 or newer, otherwise the region grouping will fail**  

## Usage
Deploy by yourself according to [docs](https://subconv.is-sb.com)  

## Contribute
Welcome issue and PR. If you want to contribute, please create a new branch from main and then create a PR to dev, or you can merge main into dev first and then make changes in dev, and finally create a PR to dev branch.  

## Credits
- [subconverter](https://github.com/tindy2013/subconverter)  
- [mihomo](https://github.com/MetaCubeX/Clash.Meta)  
- ~~[Proxy Provider Converter](https://github.com/qier222/proxy-provider-converter)~~  

## License
This project is distributed under [MPL-2.0 License](https://github.com/SubConv/SubConv-4-ZJU/blob/main/LICENSE)  
