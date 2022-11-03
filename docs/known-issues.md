---
sidebar_position: 7
---

# Known Issues

Note - This is a maintained list of known issues, bugs and proposed fixes. We will update each reported issue as they are considered and resolved. Thank you for your help and cooperation!

- Changing configuration from consumer to provider can cause the network interface to fail on reboot. The current fix is a re-flash the sd card. Don't worry, your peer configurations have been saved in your wallet. This is a known issue and re-flashing the SD will reset the files and restore network settings. You should try to remove all the partitions on the SD card - should be two - then re-partition into one large partition, then mount or 'activate' partition, then format with exfat then re-flash the SD card with a fresh (unzipped) image file (~2.4GB) insert into node and then reboot.

- DNS ERROR : "DNS resolution for boring.surf failed"  Are you SURE you are connected to 'boring'wifi?  If  DNS errors keep popping up try assigning a static ip to the Node through dhcp reservation. Adding a static IP and assigning the gateway and using 8.8.4.4 for DNS, resolved the DNS error in testing. We are actively working on a fix for this.

- Provider not online or gone forever (still listed, or still connected to as consumer target)

- Clarify what cloud and local providers are (Docs page entries for set-up for each)
- Listed/not listed provider status fed to a consumer peers status page.
- Randomized provider switching (not in this phase)
- Find new provider if this one drops (yes/no - not in this phase. An explicit setting to prevent provider switching if that is the users prefrerence)
- "Syncing peer see you at 8:30" - In response to attempted update or otherwise
- Provider status - Set message to warn consumer to find a new provider from dropdown list
- Change install config button state if user not connected to the right wifi network
- In general hide buttons that would disrupt any process if clicked out of sequence

Woring on displaying basic FAQ page showing workflows in this phase, includling temporary solutions. We appreciate your patience!
