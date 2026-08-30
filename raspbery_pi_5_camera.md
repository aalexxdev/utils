```
PRETTY_NAME="Debian GNU/Linux 12 (bookworm)"
NAME="Debian GNU/Linux"
VERSION_ID="12"
VERSION="12 (bookworm)"
VERSION_CODENAME=bookworm
ID=debian


sudo nano /boot/firmware/config.txt
----------------------------------
start_x=1
gpu_mem=256
camera_auto_detect=1
---------------------------------


sudo rpi-update


rpicam-jpeg --output test.jpg
```

