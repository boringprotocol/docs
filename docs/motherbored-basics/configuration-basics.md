---
sidebar_position: 1
---
# Configuration Basics

## - Upgrade To Boring Protocol V2 -

---
ATTENTION: - FOLLOW THESE INSTRUCTIONS TO UPGRADE THE FIRMWARE ON YOUR NODE TO V2 -

**NOTE: Even if you received a new V2 recently you will need to update the firmware to the new version of V2 by following these instructions. Subject to change based on continued bug fixes and upgrades:**

---

1. Download Phantom (Or any Solana wallet).
2. On the same device, go to the [motherbored app](https://motherbored.app) (Android users must use browser in the wallet app)
3. Authenticate with your Phantom wallet, click to sign the certificate (a popup from your wallet), then download the associated SD card image (top right) and save it, and unzip to the same directory. You will see a new 2.5GB disk image file. (Current version: 2022-10-26-boring-lite)
4. Power down the node (unplug) and carefully remove your SD card from the Pi or Motherboard node (tweezers help) and insert it into the PC SD card slot or usa an adapter. (USB/SD adaptor does work)
5. Use Balena Etcher (<https://www.balena.io/etcher/>) or Rasp Pi Imager to flash the new V2 image file to the SD card. On Windows, right-click Balena and click "Run as Administrator"
6. Once the flash is complete, remove the SD card and put SD back in Node, plug in Cat6 ethernet to your ISP router, and power up (plug-in).
7. On computer or phone, connect to new WiFi SSID called 'boring' PW: motherbored
8. Once reconnected to 'boring,' return to the [Motherbored App](https://motherbored.app/)
9. Connect your wallet again, then you will see your new V2 dashboard.
10. Choose your configuration - Select ‘Add Motherbored Consumer’ OR ‘Add Local Provider,’ ‘Add Cloud Provider(Soon),’ Coming soon: ‘Add Helium Hotspot Provider'
11. Click "Create". You will be taken to your node settings page.
12. Make any changes to SSID or password (write it down), if in consumer mode select a local provider from the list then press 'SAVE Changes' one time. This will save the file to your wallet.  
13. To activate a mode, select the configuration and press Install Config (only once). You will see the Node download a small file and reboot. (It might take a few min the first time)
14. You will need to re-connect to ‘boring’ WiFi. The node will reboot and will kick you off WiFi again while it resets.
15. Once config is installed and the system has rebooted, reestablish WiFi connection to the node, launch [Motherbored App](https://motherbored.app/) again, and press ACTIVATE just once.
16. Once activated you will see a confirmation, and the information on the bottom left of the node page will be populated (ID, Kind, Boring Setupkey, Boring PubKey) This will confirm your node is setup properly.
17. ** NOTE: If you plan to run multiple boring nodes, be sure to change the SSID at the bottom of the page so you can connect to your node again - (ex., Change to boring2, boring3, etc.) - then save.
18. Once finished, your node should be ready to use. If set to consumer mode, make sure to pick your peer in the list, then simply connect any devices you'd like to 'boring' WiFi and bore a secure path through your very own dVPN node!

If you use a consumer to connect to a provider that is not working it is not necessary to re-flash in order to re-connect to your consumer. You should be able to reach the motherbored through <https://boring.surf> to change the provider to one that is working. Use the phantom in app browser on a phone connected to the motherbored via WiFi is best.

Troubleshooting: - If you reflashed or re-configured your MotherBored you must delete the old configuration file and create a new file to upload if you find your node does not have internet. Again, recreate the provider file in motherbored.app and delete the old file. Then save and upload.

Also, if you experience issues configuring via wifi, instead of re-flashing, you can drop the boring.env file onto the boot partition using <https://boring.surf/> and just reboot. This is quicker than flashing and if it isn't a bad flash, there's no real reason to reflash again unless you cannot access the MotherBored.
(the boring.env is available to download via the [boring.env] button in the app)

***Please choose one configuration type and load it and do not change it at this time or you will be forced to re-flash your SD card to a fresh image to re-gain access to your node. We are working on a fix for this.***
Thank you for your patience, Boperators!!

-The Boring Protocol Team
