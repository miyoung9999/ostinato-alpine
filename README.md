# ostinato-alpine

An Docker Container for Use with GNS3 

This is a Dockerbuild file to create a an Alpine based container with the following installed,


Alpine Linux
Xterm
Wireshark
OStinato


Deployment 
1. CLone the repository.
2. Build the container - docker build -t ostinato-alpine .
3. Add the appliacnce to GNS3 - console is VNC.

To set up remote X framebuffer display resolution open Dockerfile and edit

ENV RESOLUTION 1920x1080x24

Thanks to 

Jan Kuri for docker container which this is based on (jkuri/alpine-xfce4)