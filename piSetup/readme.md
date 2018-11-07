These files can be dragged on the the boot partition of the RPi's SD card. This is the disk which shows when the SD card is inserted into a mac or PC. The Linux partitions are normally invisable.

ssh
a blank file. It's presence in the boot partition enables the ssh across the serial port and network

cmdline.txt
enables the serial port and console to setup the pi without having a screen

wpa_supplicant.conf 
This is a stripped down version of the wpa-supplication configuration. This is compatable with most home networks is the password and network name are added to the file. NOTE: this is not the most secure way to work if you accidently copy the complited file into a public location but is fine for most home users.
