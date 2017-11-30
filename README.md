# Linux on Chuwi Hibook
Notes about running Linux on Chuwi Hibook tablet on Fedora 27.

**Working:**

1. Video (Intel 8 gen) (Performance tip: in BIOS enable gfx boost)
2. Dock keyboard + touchpad
3. Internal USB connectors
4. Internal memory
5. Buttons: volume, power
6. Wi-Fi
7. Power Controller AXP208
8. Touchscreen GSL3680 with mainline driver (WIP mainline conf)
9. Accelerometer (working, need configuration. Needed configuration changes mainlined: https://github.com/systemd/systemd/pull/7483)
10. Audio Card (internal headphones works out-of-box, loudspeakers don't)
11. Bluetooth (working with systemd service files)


**Not working/ Not tested:**

1. Light sensor
2. SD card
3. WebCams (Front/Back)
