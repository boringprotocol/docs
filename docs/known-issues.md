---
sidebar_position: 7
---

# Known Issues / FAQ's

Note - This is a maintained list of known issues, bugs and proposed fixes. We will update each reported issue as they are considered and resolved. Thank you for your help and cooperation!

- Troubleshooting: - If you reflashed or re-configured your MotherBored you must delete the old configuration file and create a new file to upload if you find your node does not have internet. Again, recreate the provider file in motherbored.app and delete the old file. Then save and upload.

- If you are an advanced user - you can view the LOG FILES AT https://x.x.x.x:19531/browse (REPLACE X.X.X.X W/ LAN IP ADDRESS OF YOUR MOTHERBORED) You must be on the same lan as your motherbored for this to work.

- Also, if you experience issues configuring via wifi, instead of re-flashing, you can drop the boring.env file onto the boot partition using <https://boring.surf> and just reboot. This is quicker than flashing and if it isn't a bad flash, there's no real reason to reflash again unless you cannot access the MotherBored. (the boring.env is available to download via the [boring.env] button in the app)

- ** NOTE: If you plan to run multiple boring nodes - be sure to change the SSID at the bottom of the page so you can connect to your node again - (ex., Change to boring2, boring3, etc.) - then save.

- We pushed an update designed to address the DNS error for boring.surf last night. Please re-flash your SD cards with the new 2023-01-03-boring-lite image available at <https://motherbored.app/>. The new image also includes an updated OTA (over the air) update feature that should pull in future updates upon a reboot of the node so you should not need to re-flash again.  

Those having DNS error issues configuring their MotherBored should download the new image from <https://motherbored.app/>, flash their SD cards (ensure the boot partition is removed prior to flashing), install sd, boot motherbored, connect to 'boring' wifi and configure. Let me know how it goes. Thanks for your patience!  

- Changing configuration from consumer to provider can cause the network interface to fail on reboot. The current fix is a re-flash the sd card. Don't worry, your peer configurations have been saved in your wallet. This is a known issue and re-flashing the SD will reset the files and restore network settings. You should try to remove all the partitions on the SD card - should be two - then re-partition into one large partition, then mount or 'activate' partition, then format with exFAT then re-flash the SD card with a fresh (unzipped) image file (~2.4GB) insert into node and then reboot.

- DNS ERROR : "DNS resolution for boring.surf failed"  Are you SURE you are connected to 'boring' wifi?  If  DNS errors keep popping up try assigning a static ip to the Node through dhcp reservation. Adding a static IP and assigning the gateway and using 8.8.4.4 for DNS, resolved the DNS error in testing. We are actively working on a fix for this.

- Provider not online or gone forever (still listed, or still connected to as consumer target)

- Clarify what cloud and local providers are (Docs page entries for set-up for each)
- Listed/not listed provider status fed to a consumer peers status page.
- Randomized provider switching (not in this phase)
- Find new provider if this one drops (yes/no - not in this phase. An explicit setting to prevent provider switching if that is the user's preference)
- Provider status - Set message to warn consumer to find a new provider from dropdown list
- Change install config button state if user not connected to the right wifi network
- In general hide buttons that would disrupt any process if clicked out of sequence

Working on displaying basic FAQ page showing workflows in this phase, including temporary solutions. We appreciate your patience!
