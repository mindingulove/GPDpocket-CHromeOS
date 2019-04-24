# GPDpocket-ChromeOS
Chrome OS builds for GPD pocket created using Project Croissant ( https://github.com/imperador/chromefy )

Download link ( https://drive.google.com/drive/folders/13AOEMCLCEi1mqFs3ABFlGE3JlbrNovai?usp=sharing )

1) Use Etcher to create bootable USB drive (https://www.balena.io/etcher/)
2) Boot the live usb pressing FN + F7
3) When loaded press CTRL + ALT + F2 and enter in shell
4) Login with chronos
5) type in:
6) sudo su
7) cd /
8) sudo   /usr/sbin/chromeos-install  --dst  /dev/mmcblk0  --skip_postinstall
9) Reboot and enjoy
