---
sidebar_position: 5
---

# Configuration Basics

UPDATED - V1 to V2 upgrade instructions:
*Instructions subject to change based on continued fixes and upgrades: 

1. Download Phantom (Solana wallet)
2. Go to https://motherbored.app/
3. Authenticate with your Phantom wallet, sign the certificate (popup from your wallet), then download the associated SD card image (top right) and save it and unzip to same directory. You will see your 2.4GB disk image file. 
4. Carefully remove your SD card from the Pi or Motherboard and inert into PC
5. Use Balena Etcher (https://www.balena.io/etcher/) or Rasp Pi Imager to flash the new V2 image file to the SD card 
6. Once complete, put SD back in Node, plug in Cat6 ethernet, then power up
7. On computer or phone, connect to new SSID - > 'boring' PW: motherbored 
8. a. Once reconnected to 'boring', return to https://motherbored.app/
    b. Connect your wallet again, then you will see your new V2 dashboard. 
    c. Select ‘Add Motherbored Consumer’ OR ‘Add Motherbored Provider’, ‘Add Cloud Provider(Soon)’, or ‘Add Helium Hotspot Provider (soon).’
    d. Choose your option, then press INSTALL CONFIG (only once). The Node will download and reboot. (It might take a few min the first time)
9. Confirm you are still connected to ‘boring’ - again, the node will reboot and may temporarily kick you off while it resets.
10. Once config is installed and the system rebooted, WiFi reconnected, launch https://motherbored.app/ again, then PRESS ‘Activate’ (only once).
11. Once Activated - you will see a confirmation, and the information on the bottom left of the node page will be filled out (ID, Kind, Boring Setupkey, Boring PubKey) this will confirm you are good to go and setup properly.
** NOTE: If you plan to run multiple boring nodes - be sure to change the SSID at the bottom of the page so you can connect to your node again - (ex., Change to boring2, boring3, etc.) - then save. 

Once finished, your node should be set and ready to use. If set to consumer mode make sure to pick your peer in the list then simply connect any devices you want to 'boring' WIFI and bore a secure path through your very own dVPN node!
Thanks for your patience, Boperators!!
