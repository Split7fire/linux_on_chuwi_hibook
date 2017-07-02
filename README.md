# Linux on Chuwi Hibook
Notes about running Linux on Chuwi Hibook tablet

**Working:**

1. Video (Intel 8 gen)
2. Dock keyboard + touchpad
3. Internal USB connectors
4. Internal memory
5. Buttons: volume, power (as of kernel 4.12)
6. Wi-Fi & bluetooth (as of 4.12 kernel module in mainline kernel) !!! Firmware needed
7. Power Controller AXP208 (As of 4.12 - needs enabling in config)
8. Touchscreen GSL3680 with out-of-tree driver (https://github.com/onitake/gslx680-acpi). !!! Firmware needed (https://github.com/onitake/gsl-firmware/tree/master/firmware/chuwi/hibook && https://github.com/Split7fire/gsl-firmware)
9. Accelerometer (as of 4.12.rc6)

**Not working/ Not tested:**

1. Light sensor
2. Audio card (ALC 5651)
3. SD card
