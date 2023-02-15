---
sidebar_position: 4
---

# Add Cloud Provider

1. First create a Provider Peer in the Motherbored interface in the [Motherbored App!](https://motherbored.app)

2. Download boring.env file using the button - use this config on your server at /boot/boring.env

## SSH into your cloud provider server

```
`ssh root@[IP]`
```

## The Boring Config

```
`vi /boot/boring.env`
```

- Paste the boring.env config file that was downloaded
and save.

## The Boring Installer

- Download and run the installer.

```
wget https://s3.us-east-2.amazonaws.com/boringfiles.dank.earth/install.sh
chmod +x install.sh
./install.sh
```

---

### Forgot to get the config? or need to use a different config


- Edit the /boot/boring.env and:

```
systemctl restart boring
```

SETUP NOTES - Adaptor is eth0 - All Ports closed - Use public IP

- The default ethernet adapter is configured as eth0, if your server is different (ens16), we need to modify the boring. env config file.

- Firewall Ports: At this time we recommend keeping all ports closed.

- A public IP is required.

- NetBird binary - Default server config has NetBird in /bin. If you have the netbird binary in /usr/bin/ instead of /bin you will need to edit the config.
