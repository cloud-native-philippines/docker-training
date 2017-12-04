# Installation

## Mac OS

Download and install using Docker for Mac: [https://docs.docker.com/docker-for-mac/install/](https://docs.docker.com/docker-for-mac/install/)

## Ubuntu

Follow the instructions at https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/\#install-docker-ce

```
# Update the apt package index
sudo apt-get update

# Install packages to allow apt to use a repository over HTTPS
sudo apt-get install -y apt-transport-https ca-certificates curl software-properties-common

# Add Docker’s official GPG key:
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

# Set up the stable repository (amd64)
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"

# Update the apt package index
sudo apt-get update

# Install the latest version of Docker CE
sudo apt-get install -y docker-ce

# If you would like to use Docker as a non-root user, add it to the "docker" group
sudo usermod -aG docker $(whoami)
```



