#Radiodan Pi Quick Provisioner

A set of scripts and configs to take a octo pi to a radiodan.

##How to

These instructions assume you're starting from a blank disk image of Octopi.

1. Log into the Raspberry Pi
2. `sudo raspi-config` to Expand filesystem and Overclock (900MHz)
3. Restart and log in again
4. `git clone https://github.com/mansehr/provision`
5. `cd provision`
6. `sudo ./provision wpa`

You can view all the possible steps by running `./provision`.
Setting a `LOG_LEVEL` environment variable to `info` will hide the output of the provisioning commands.



##Alternative configuration?
http://www.daveconroy.com/turn-your-raspberry-pi-into-a-wifi-hotspot-with-edimax-nano-usb-ew-7811un-rtl8188cus-chipset/
