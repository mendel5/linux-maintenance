# linux-maintenance
Maintenance terminal commands for Linux

## Part 1
Use mainly these commands:

```
sudo apt clean

sudo apt-get autoremove --purge

sudo apt update

sudo apt upgrade

sudo apt dist-upgrade
```

## Part 2
```
sudo apt autoclean

sudo apt autoremove

sudo apt install baobab

sudo baobab

neofetch
```

## Other
```
#!/bin/bash
[ -d /sys/firmware/efi ] && echo UEFI || echo BIOS
```

Source:
- https://askubuntu.com/questions/162564/how-can-i-tell-if-my-system-was-booted-as-efi-uefi-or-bios

More links:
- https://dannyda.com/2021/05/05/how-to-find-out-if-the-ubuntu-20-04-1-lts-os-disk-is-mbr-or-gpt-for-linux-debian-kali-linux-centos-fedora-etc-steps-are-very-similar-with-slightly-different-commands/
- https://dannyda.com/2021/05/07/how-to-convert-ubuntu-20-04-1-lts-os-disk-from-mbr-to-gpt-gpt-to-mbr-without-losing-data/
- https://dannyda.com/2021/05/08/how-to-convert-ubuntu-20-04-1-lts-from-bios-to-uefi/

## Links
- https://wiki.ubuntuusers.de/Systempflege/
- https://askubuntu.com/questions/984797/clean-autoclean-and-autoremove-combining-them-is-a-good-step
