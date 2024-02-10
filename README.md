# init-Linux-Nodes
Install Linux Node - mango tests

## Purpose of this repo
Help newbie Linux people to install crypto project nodes easier

## Step 1 - secure the node install with a fresh user

Create a new Linux user called 'mango' :
```bash
# Become root
sudo su
# create new user 
adduser -q mango
# carefully input mango password then...
# ...become mango
su - mango
```

## Step 2 - install and launch scripts
```sh
sudo apt install -y git
git clone https://github.com/LeChatNoir69/init-Linux-Nodes

...To complete
```
