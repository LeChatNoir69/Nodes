# init-Linux-Nodes
Install Linux Node - mango tests

## Purpose of this repo
Help newbie Linux people to install crypto project nodes easier

## Step 1 - Secure the node install with a fresh user

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

## Step 2 - Install and launch init scripts
```sh
sudo apt install -y git
git clone https://github.com/LeChatNoir69/init-Linux-Nodes
cd init-Linux-Nodes
./init
```
If everything went well, you should start your mango node and wallet.
