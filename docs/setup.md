# Setup Guide
<img align="right" width="290" height="290" src="logob.png" />

[![Docker Pulls](https://img.shields.io/docker/pulls/planckscloud/plancks-cloud.svg?maxAge=86400)](https://hub.docker.com/r/planckscloud/plancks-cloud)
<img src="https://europe-west1-captains-badges.cloudfunctions.net/function-clone-badge-pc?project=plancks-cloud/plancks-cloud" /><br />

## Pre-install
- Give your "server" a static IP on the network. Routers typically allow you to do this under DHCP server settings.
- Create a NAT (DST-NAT) rule on your router to point at your servers's static IP address for TCP 80 and TCP 443.
- Install docker on your server.
- Run `docker swarm init` on your server.
- Run `docker service ls` to check your setup. If if gives an error, docker swarm probably won't work.

## Installation
### Install the CLI
Either
- `go get github.com/plancks-cloud/plancks-cli`

or 
- Run installer at <a href="https://github.com/plancks-cloud/plancks-cli/releases">https://github.com/plancks-cloud/plancks-cli</a>

### Install the Daemon
- TBA


