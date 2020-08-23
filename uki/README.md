# Setup:

## Copy Stuff:
```
cp 90-mkinitcpio-install.hook /etc/pacman.d/hooks/
mkdir -p /usr/local/share/libalpm/scripts/
cp mkinitcpio-install /usr/local/share/libalpm/scripts/
mkdir -p /usr/local/sbin/uki/
cp create-uki splash-arch.bmp kernel-command-line.txt /usr/local/sbin/uki/
cp <your-db.crt> /usr/local/sbin/uki/db.crt
cp <your-db.key> /usr/local/sbin/uki/db.key
chmod o= /usr/local/sbin/uki/db.crt
chmod o= /usr/local/sbin/uki/db.key
```
