---
sidebar_position: 5
---

## - Upgrade The Boring Protocol V2 -

---
ATTENTION: - FOLLOW THESE INSTRUCTIONS TO UPGRADE THE FIRMWARE ON YOUR NODE TO V2 -

 <i>NOTE: Even if you recieved a new V2 recently you will need to update the firmware to the new verson of V2 by following these instructions. Subject to change based on continued bug fixes and upgrades:</i>

---

1. Download Phantom (Or any Solana wallet).
2. On the same device, go to https://motherbored.app/ (Android users must use browser in the wallet app)
3. Authenticate with your Phantom wallet, click to sign the certificate (a popup from your wallet), then download the associated SD card image (top right) and save it, and unzip to the same directory. You will see a new 2.5GB disk image file. (Current version: 2022-10-26-boring-lite) 
4. Power down the node (unplug) and carefully remove your SD card from the Pi or Motherboard node (tweesers help) and insert it into the PC SD card slot or usa an adapter. (USB/SD adaptor does work)
5. Use Balena Etcher (https://www.balena.io/etcher/) or Rasp Pi Imager to flash the new V2 image file to the SD card. On Windows, right-click Balena and click "Run as Administrator" 
6. Once the flash is complete, remove the SD card and put SD back in Node, plug in Cat6 ethernet, and power up (plug-in).
7. On computer or phone, connect to new SSID - > 'boring' PW: motherbored 
8. Once reconnected to 'boring,' return to https://motherbored.app/    
9. Connect your wallet again, then you will see your new V2 dashboard.     
10. Choose your onfiguration - Select ‘Add Motherbored Consumer’ OR ‘Add Local Provider,’ ‘Add Cloud Provider(Soon),’ <i>Coming soon: ‘Add Helium Hotspot Provider'</i>
11. Click your option, Make any changes to SSID or password (write it down), then press SAVE Config one time. This will save the file to your wallet. 
12. To activate a mode, select the configuration and press Install Config (only once). You will see the Node download a small file and reboot. (It might take a few min the first time)
 
13. You will need to re-connect to ‘boring’. The node will reboot and will kick you off WiFi again while it resets.
14. Once config is installed and the system has rebooted, reestablish WiFi connection to the node, launch https://motherbored.app/ again, and press ACTIVATE just once.
15. Once activated you will see a confirmation, and the information on the bottom left of the node page will be populated (ID, Kind, Boring Setupkey, Boring PubKey) This will confirm your node is setup properly.
16. ** NOTE: If you plan to run multiple boring nodes, be sure to change the SSID at the bottom of the page so you can connect to your node again - (ex., Change to boring2, boring3, etc.) - then save. 
17. Once finished, your node should be ready to use. If set to consumer mode, make sure to pick your peer in the list, then simply connect any devices you'd like to 'boring' WiFi and bore a secure path through your very own dVPN node!

<b>Thank you for your patience, Boperators!!

-The Boring Protocol Team