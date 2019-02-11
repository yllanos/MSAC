# MSAC
#### Deploy your own media server via code


## What this is

This repo hosts several sub-projects which will allow yo to set up a personal media server, ready for use. You will have to choose a the project that more closely resembles your needs and configure accordingly.

So in general, you could just pick a project, alter some variables on text files and deploy your server to have it running in no time.

The projects rely on Ansible and Docker for services/infrastructure deployment and as containers/packages we will use:

* [Plex Media Server](https://hub.docker.com/r/linuxserver/plex)
* [Sonarr](https://hub.docker.com/r/linuxserver/sonarr)
* [Radarr](https://hub.docker.com/r/linuxserver/radarr)
* [Jackett](https://hub.docker.com/r/linuxserver/jackett)
* [Tautulli](https://hub.docker.com/r/linuxserver/tautulli)
* [Organizr](https://hub.docker.com/r/lsiocommunity/organizr)
* [Deluge](https://hub.docker.com/r/linuxserver/deluge)
* [RuTorrent](https://hub.docker.com/r/linuxserver/rutorrent)
* [Grafana](https://grafana.com/)
* [Portainer](https://www.portainer.io/)
* [NextCloud](https://hub.docker.com/r/linuxserver/nextcloud)
* [Ubooquity](https://hub.docker.com/r/linuxserver/ubooquity)
* [Webmin](http://www.webmin.com/)



## Requirements

* Control machine with Ansible installed. I recommend a Linux or MacOS machine for this part.
* Server or node with Python installed. 
* Both control machine and server/node should be able to communicate via port 22 (SSH). I also recommend passwordless login. --Steps 5 and 6 [as shown here](https://medium.com/@tushar0618/install-and-configure-ansible-on-ubuntu-ea9be8107061)--


## Clone this project

```bash
git clone https://github.com/yllanos/MSAC.git
```

## Available projects


Please pick a project:

#### Project 1: Chiminigagua

Single control machine to server. Every service will be a docker container

Access documentation and setup instructions [here](01/README.md)



## Issues




## Have fun! :sunglasses:

Please :pray: report any [issues](https://github.com/yllanos/MSAC/issues) you may encounter
