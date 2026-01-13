```bash
diskutil list external

diskutil partitiondisk disk2 mbr fat32 MYFAT32 8G exfat MyExFAT R

xattr -c win.iso

hdiutil attach win.iso

cd /Volumes/CCCOMA_X64FRE_EN-US_DV9

rsync -r -t --exclude=sources/install.wim . /Volumes/MYFAT32
cp sources/install.wim /Volumes/MyExFAT
```
