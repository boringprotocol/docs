---
sidebar_position: 7
---

# Known Issues / FAQ's

Note - This is a maintained list of known issues, bugs and proposed fixes. We will update each reported issue as they are considered and resolved. Thank you for your help and cooperation!

- If you are an advanced user - you can view the LOG FILES AT https://x.x.x.x:19531/browse (REPLACE X.X.X.X W/ LAN IP ADDRESS OF YOUR MOTHERBORED) You must be on the same lan as your motherbored for this to work.

- Also, if you experience issues configuring via wifi, instead of re-flashing, you can drop the boring.env file onto the boot partition using <https://boring.surf> and just reboot. This is quicker than flashing and if it isn't a bad flash, there's no real reason to reflash again unless you cannot access the MotherBored. (the boring.env is available to download via the [boring.env] button in the app)

- If you plan to run multiple boring nodes - be sure to change the SSID at the bottom of the page so you can connect to your node again - (ex., Change to boring2, boring3, etc.) - then save.

- If your consumer connects to a provider that is not working it is not necessary to re-flash in order to re-connect and change the provider. You should be able to reach the motherbored through <https://boring.surf> to connect and change the provider to one that is working. Using the phantom in app browser on a phone seems to work more consistently.

- Those having DNS error issues configuring their MotherBored should download the new image from <https://motherbored.app/>, flash their SD cards (ensure the boot partition is removed prior to flashing), install sd, boot motherbored, connect to 'boring' wifi and configure. Let me know how it goes. Thanks for your patience!  

- Changing configuration from consumer to provider can cause the network interface to fail on reboot. The current fix is a re-flash the sd card. Don't worry, your peer configurations have been saved in your wallet. This is a known issue and re-flashing the SD will reset the files and restore network settings. You should try to remove all the partitions on the SD card - should be two - then re-partition into one large partition, then mount or 'activate' partition, then format with exFAT then re-flash the SD card with a fresh (unzipped) image file (~2.4GB) insert into node and then reboot.

- DNS ERROR : "DNS resolution for boring.surf failed"  Are you SURE you are connected to 'boring' wifi?  If  DNS errors keep popping up try assigning a static ip to the Node through dhcp reservation. Adding a static IP and assigning the gateway and using 8.8.4.4 for DNS, resolved the DNS error in testing. We are actively working on a fix for this.

- Clarify what cloud and local providers are (Docs page entries for set-up for each)
- Listed/not listed provider status fed to a consumer peers status page.
- Randomized provider switching (not in this phase)
- Find new provider if this one drops (yes/no - not in this phase. An explicit setting to prevent provider switching if that is the user's preference)
- Provider status - Set message to warn consumer to find a new provider from dropdown list
- Change install config button state if user not connected to the right wifi network
- In general hide buttons that would disrupt any process if clicked out of sequence

- Working on displaying basic FAQ page showing workflows in this phase, including temporary solutions. We appreciate your patience!
