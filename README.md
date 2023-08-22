# FWWCP Sandbox Local Development

This repository has been adapted from sunnythepatel/omeka-classic-docker-image

You can use this repository to run a version of the [FWWCP Website](http://fwwcpdigitalcollection.org/). We use docker, and the image for the Omeka installation defaults to a ARM64 (Mac OS compatible) image. If you are using windows, you will need to rebuild the omeka docker image using the provided Dockerfile.

## Getting Started (with Mac OS)

1. First, install [Docker](https://docs.docker.com/desktop/install/mac-install/)
2. Clone the Repository and install git submodules

```
git clone git@github.com:systemizer/omeka-classic-docker-image.git
cd omeka-classic-docker-image
git submodule update --init
```

3. Run the website using docker-compose
```
docker-compose up -d
```

4. The website should now be working. Open a browser and navigate to [localhost:8081](http://localhost:8081)
