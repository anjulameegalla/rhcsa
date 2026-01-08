### linux filesystem hierarchy

- /bin - executable binaries (/usr/bin)
- /sbin - system binaries (su)
- /lib - libraries
  - /lib/modules - kernel modules
- /opt - additional software
- /boot - booting
  - /boot/grub2 - bootloader (grub.cfg)
- /etc - system config
- /home - user dir
- /root - root user dir
  - kickstart installation (anaconda-ks.cfg)
- /srv - served by system (server, service)
- /media - removable media
- /mnt - temporary mount images
- /tmp - %temp% files (/var/tmp)
- /dev - hardware devices
  - /dev/null - data black hole
- /proc - process info
- /var - variable data
  - /var/log - logs
- /sys - virtual filesystem


---


### man pages (manuals)

```bash
# access man pages
man <command>
man <file_name>
man <service_name>

# access help menu
<commands> --help

# summarized description
whatis <command>

# file location/ man location
whereis <comamnd> 

# manual of man command
man man
```




























[32 30 32 36 2D 30 31 2D 30 38]::