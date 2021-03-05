
<div align="center">
  <img src="AAUgraphics/aau_logo.png" height="100">
</div>

# Riotpot <a href="https://github.com/aau-network-security/riotpot/actions"><img alt="GitHub Actions status" src="https://github.com/aau-network-security/riotpot/workflows/cyber/badge.svg"></a> 


## Table of Contents
- [Riotpot](#riotpot-) <!-- no toc -->
  - [Table of Contents](#table-of-contents)
  - [1. Description](#1-description)
  - [2. Installation](#2-installation)


## 1. Description
Riotpot is an interoperable medium interaction honeypot, primarly focused on the emulation IoT and OT protocols, althoug, it is also capable of emulating other services.

This services are loaded in the honeypot in the form of plugins, making Riotpot a modular, and very transportable honeypot. The services are loaded at runtime, meaning that the weight of the honeypot will vary on premisses, and the services loaded e.g. HTTP, will only be used when required.

## 2. Installation


### Docker
```bash
docker-compose up -d --build
```
### Local

```bash
go build -o bin/
```

Specific file testing (e.g. plugins):
```bash
go run Path
```