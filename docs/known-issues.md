---
sidebar_position: 7
---

# Known Issues

Note - This is a rough and running list of known issues, bugs and proposed fixes. We will update each reported issue as they are considered and resolved. Thank you for your help and cooperation!

 1. Changing configuration from consumer to provider can cause the network interface to fail on reboot. The current fix is a re-flash the sd card. Don't worry, your peer configurations have been saved in your wallet. This is a known issue and re-flashing the SD will reset the files and restore network settings. You should try to remove all the partitions on the SD card - should be two - then re-partition into one large partition, then mount or 'activate' partition, then format with exfat then re-flash the SD card with a fresh (unzipped) image file (~2.4GB) insert into node and then reboot. 

2. DNS ERROR : "dns resolution for boring.surf failed, are you SURE you are connected to 'boring'wifi? We are actively working on a fix for this. 

2. Provider not online or gone forever (still listed, or still connected to as consumer target)

- clarify what a cloud and local providers are (docs page entries for set-up for each)
- listed/not listed provider status fed to a consumer peers status page so they know if they should find another peer if the one they were connected to is either not online or possible gone forever.
- randomized provider switching (not in this phase)
- find new provider if this one drops (yes/no - not in this phase. A explicit setting to prevent provider switching if that is the users prefrerence)
- "syncing peer see you at 8:30" - every time I try to update or anything
- provider status - Set message to warn consumer to find a new provider feom dropdown list
- change install config button state if user not connected to the right wifi network?
- In general hide/show buttons that would disrupt any set-up process if clicked out of sequence.
- Woring on displaying basic faq page showing workflows in this phase (even if only temporary solutions)