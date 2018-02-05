## Ubuntu Dockerfile


This repository contains **Dockerfile** of [Ubuntu](http://www.ubuntu.com/) for [Docker](https://www.docker.com/)'s [automated build](https://hub.docker.com/r/library/ubuntu/)

## CMurphi5.4.9.1
[automated build](http://mclab.di.uniroma1.it/site/index.php/software/18-cmurphi)


### Base Docker Image

* [ubuntu:16.04](https://hub.docker.com/r/library/ubuntu/)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://hub.docker.com/r/rabenda/ubuntuwithcmurphi/) from public [Docker Hub Registry](https://hub.docker.com/): `docker pull rabenda/ubuntuwithcmurphi`

   (alternatively, you can build an image from Dockerfile: `docker build -t="rabenda/ubuntuwithcmurphi" github.com/rabenda/ubuntuwithcmurphi`)


### Usage

    docker run -it --rm rabenda/ubuntuwithcmurphi
