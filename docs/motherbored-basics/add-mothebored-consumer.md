---
sidebar_position: 2
---

# Add Consumer access - Use your MotherBored to connect to a local provider

## Select ‘Add Motherbored Consumer to surf securly using the Boring dVPN.’

1. Connect to your MotherBored's WIFI (Default SSID 'boring' PW: motherbored)
    - Launch [Motherbored App!](https://motherbored.app) (Andriod users must use in wallet browser)
    - Select ‘Add Motherbored Consumer' button.
    - On the next page 'NEW CONSUMER PEER' please choose the peer name you want to use. Toggle with arrow. Then press 'CREATE' once
    - On the next page configure your local WiFi settings (SSID, Password, and Channel) - Once done press 'Save Changes'. You will see the message 'Syncing peer'.
    - When ready to activate press 'INSTALL CONFIG' just once. The Node will download your configuration and reboot. It might take a few min the first time.

2. Once rebooted (3 min) confirm you are reconnected to your motherbored WiFi SSID to proceed. If this is the first time setting up your MotherBored proceed to the next step otherwise your MotherBored is now ready to use in Consumer Mode.

3. If this is the first time setting up your MotherBored this is when you activate it. Once config is installed, the system is rebooted, and WiFi is reconnected,
 launch [Motherbored App](https://motherbored.app) again, Select your then press ACTIVATE just once.

4. Once activated you will see a confirmation, and the information on the bottom left of the node page will be filled out.
 (ID, Kind, Boring Setupkey, Boring PubKey) this will confirm you are good to go and setup properly.

** NOTE:

If you plan to run multiple boring nodes, be sure to change the SSID and the WiFi Channel at the bottom of the page so you can connect to your node again - (ex., Change to boring2, boring3, etc.) - then save.

Once finished, your node should be ready to use. If set to consumer mode, make sure to pick your peer in the list then simply connect any devices you'd like to 'boring' WiFi and bore a secure path through your very own dVPN node!

Additional Information: - If you reflashed or re-configured your Provider MotherBored you may need to delete the old configuration file and create a new file to upload if you find your node does not have internet. Again, recreate the provider file in motherbored.app and delete the old file. Then save and upload.

Also, if you experience issues configuring via wifi, instead of re-flashing, you can drop the boring.env file onto the boot partition using <https://boring.surf> and just reboot. This is quicker than flashing and if it isn't a bad flash, there's no real reason to reflash again unless you cannot access the MotherBored.

The latest firmware is always available to download via the [boring.env] button in the [Motherbored App!](https://motherbored.app)

