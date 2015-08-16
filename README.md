# docker-nodejs

[![](https://badge.imagelayers.io/sys42/docker-nodejs:latest.svg)](https://imagelayers.io/?images=sys42/docker-nodejs:latest 'Get your own badge on imagelayers.io')

NodeJS (iojs) installed locally in a Docker Container.

Since many NodeJS extensions require native compilation this image is based on [sys42/docker-build-essentials](https://github.com/sys42/docker-build-essentials).

Additionally it contains:

  * nvm: locally installed in user's app home directory
  * NodeJS (iojs): locally installed in user's app home directory
  
  **NOTE:** An very old or slow machines the startup of a container may take some time due to the dynamic uid/gid remapping and the nature of a local node installation (many files in and below the user's home directory).

For generic usage informations please examine [the README file of the base image](https://github.com/sys42/docker-base).
