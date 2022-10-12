---
sidebar_position: 3
---

# Add Cloud Provider


1. First create a Provider Peer in the Motherbored interface at https://motherbored.app
2. Download boring.env and use this config on your server at /boot/boring.env )

## SSH into your server

`ssh root@[IP]`


## The Boring Config

`vi /boot/boring.env` 

Paste the boring.env config file that was downloaded
and save.

## The Boring Installer

download and run the installer

```
wget https://s3.us-east-2.amazonaws.com/boringfiles.dank.earth/install.sh
chmod +x install.sh
./install.sh
```

Congrats, you're done!


---
### forgot to get the config? or need to use a different config 

edit the /boot/boring.env and:

```
systemctl restart boring
```
