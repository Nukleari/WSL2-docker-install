# WSL2-docker-install
install script for docker in wsl2

install: `curl https://raw.githubusercontent.com/Nukleari/WSL2-docker-install/main/install-docker | /bin/bash`

before install make sure docker is not installed eg: `sudo apt remove docker docker-engine docker.io containerd runc`

The script currently supports debiand and ubuntu.
It will install docker, add the current user to the docker group, create a startup script, add the script to the .bashrc, enables the docker group to start the docker daemon without a password
