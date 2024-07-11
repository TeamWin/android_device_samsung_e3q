# TWRP Device Tree for Samsung Galaxy S24 Ultra

## For Decryption
[Install Instructions](https://xdaforums.com/t/sm-s928b-0-userdata_aio-odin-flashable-to-automatically-remove-encryption-make-rom-rw-install-twrp-root-use-on-stock-firmware-unlocked-bootloaders.4660645/)

# Special Thanks 
[jrkruse](https://xdaforums.com/m/jrkruse.1949695/) For userdata aio script.

## Clone repo
```bash 
git clone -b android-12.1 https://github.com/Archer3770/twrp_device_samsung_e3q device/samsung/e3q
```

## To build 
```bash
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_e3q-eng
mka recoveryimage
```
