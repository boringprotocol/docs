---
sidebar_position: 3
---

# Add Local Provider

Instructions are subject to change based on develpoer updates:

## Select ‘Add Motherbored Provider’

```
1. Choose your option, then press INSTALL CONFIG (only once). 
The Node will download and reboot. (It might take a few min the first time)

```

```
2. Confirm you are still connected to ‘boring’ WIFI - again, 
the node will reboot and may temporarily kick you off while it resets.

```

```
3. Once config is installed and the system rebooted, WiFi reconnected,
launch https://motherbored.app/ again, then PRESS ‘Activate’ (only once).

```

```
4. Once Activated - you will see a confirmation, and the information on the bottom
 left of the node page will be filled out (ID, Kind, Boring Setupkey,
 Boring PubKey) this will confirm you are good to go and set up properly. 

```

```
5. Once finished, your node should be set and ready to use. 
If set to consumer mode mke sure to pick your peer in the list then simply connect
any devices you want to 'boring' WIFI and bore a secure path through your very own dVPN node!

```
Troubleshooting: - If you reflashed or re-configured your MotherBored you must delete the old configuration file and create a new file to upload if you find your node does not have internet. Again, recreate the provider file in motherbored.app and delete the old file. Then save and upload.

Also, if you experience issues configuring via wifi, instead of re-flashing, you can drop the boring.env file onto the boot partition using <https://boring.surf> and just reboot. This is quicker than flashing and if it isn't a bad flash, there's no real reason to reflash again unless you cannot access the MotherBored.
(the boring.env is available to download via the [boring.env] button in the app)

** NOTE: If you plan to run multiple boring nodes - be sure to change the SSID at the bottom of the page so you can connect to your node again - (ex., Change to boring2, boring3, etc.) - then save.
