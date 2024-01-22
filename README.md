# brewOS-Linux
Custom Linux distro for Playstation 3 based on Gentoo. WIP.
# Current ideas
- Versioning system<br>
  The versioning system for brewOS will be similar to Android, but instead be names of minerals. The original idea for this distro was to call it moyaiOS, but brewOS fits better as its a distro for homebrewed PS3s.
- Custom drivers for the PS3 hardware<br>
  Kernel drivers for SYSCON, and overall improvements to kernel to make it PS3 friendly.<br>
  Heavily optimize the DE and running processes to make it as smooth as possible, while using the constraints of the decade old hardware.<br>
  RSX-swap to be enabled by default, giving a super fast swap space. HDD-swap will also be present, but can be disabled by the user if desired (not recommended)
# Installation procedure
Format PS3 HDD to add OtherOS region.<br>Downloads the LiveCD and copy the files to a USB.<br>Mount HDD using this command: `mkdir /mnt/ps3dd1 && mount /dev/ps3dd1 /mnt/ps3dd1` (may be ps3da1 on phat consoles)<br>Download stage4 and untar it to `/mnt/ps3dd1`.<br>Reboot and select the Gentoo option from Petitboot.<br>Default login is `ps3`, password `ps3`. `root` password is `root`.
# Development team
[kernaltrap](https://github.com/kernaltrap8): Original idea, lead develiper

[Hydrogen (Ellie)](https://github.com/Hydrogen8): Ideas, second lead developer
