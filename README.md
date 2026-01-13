```bash
diskutil list
diskutil eraseDisk ExFAT WIN10 GPT diskX

open Win11_25H2_English_x64.iso
cd /Volumes/CCCOMA_X64FRE_EN-US_DV9
sudo cp -r . /Volumes/WIN10/

cd ~
diskutil eject /Volumes/WIN10
diskutil eject /Volumes/CCCOMA_X64FRE_EN-US_DV9
```
