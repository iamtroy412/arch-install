# Home Arch Install

### Prepare media
- Download the ISO using one of the methods from the Arch website
- Put the ISO onto the USB flash drive

```
sudo dd if=archlinux-2023.03.01-x86_64.iso of=/dev/rdisk2 bs=1m
```

### Boot installation media
- Check to make sure we booted EFI

```
ls /sys/firmware/efi/efivars
```
