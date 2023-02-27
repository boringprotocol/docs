---
sidebar_position: 3
---

# Add Local Provider - ($BOP Rewards have started!)

Instructions for adding a local provider to the Boring Network - earn $BOP by providing internet security and access for Boperator Consumers. Instructions are subject to change based on developer updates:

## Adding a Motherbored Provider to the Network

1. Power up your MotherBored and connect to it's WiFi (default SSID: boring pw: motherbored)

1. Connect to your MotherBored at [Motherbored App!](https://motherbored.app) It will Prompt you to connect your Solana wallet application where you will configure and save your setup files. Sign the popup from the wallet if asked.

1. You will now be in your MotherBored app where you can add, remove or change your MotherBored configuration files as necessary. Choose 'Add Motherbored Provider'.

1. On the next screen you will see "NEW PROVIDER PEER" and a randomized name will be generated for your node. You can change it if you like but the default is usually fine. Confirm the 'local' box is checked and press 'Create' only once.

5. You will be taken to the setup page for your provider node. Here you can modify your SSID and password you will use to access the wifi in order to make configuration changes to your node. Again the WiFi for a provider node is only used to reconfigure your MotherBored if necessary.

6. Once you are happy with the SSID and password and WIFI Channel (Choose one that does not interfere with existing WiFi signals) then press Save Changes only once. You will See the message "Changes saved, press install config to Activate"

7. Press Install Config once. This will upload the file to your motherbored
your Node will download any updates and reboot. (It might take a few min the first time as encryption keys are created)

2. Once the node updates and reboots you must reconnect to the new WiFi SSID and password you created to Activate the Node on our network. Confirm you are connected to the MotherBored WiFi and launch [Motherbored App](https://motherbored.app) again, then PRESS ‘Activate’ (only once). This adds your encryption key and adds you to the provider list shown on consumer devices.

4. Once Activated - you will see a confirmation, and the information on the bottom
 left of the node page will be filled out (ID, Kind, Boring Setupkey,
 Boring PubKey) this will confirm you are good to go and set up properly.

5. Once finished, your node should be set and ready to provide secure access for consumers. Sit back relax and enjoy the rewards.

NOTES:

Also, if you experience issues configuring via wifi, instead of re-flashing, you can drop the boring.env file onto the boot partition using <https://boring.surf> and just reboot. This is quicker than flashing and if it isn't a bad flash, there's no real reason to reflash again unless you cannot access the MotherBored.
(the boring.env is available to download via the [boring.env] button in the app)

** NOTE: If you plan to run multiple boring nodes - be sure to change the SSID at the bottom of the page so you can connect to your node again - (ex., Change to boring2, boring3, etc.) - then save.
