# Manjaro-bootsplash-amd
Kernel Bootsplash theme for manjaro Linux using AMD logo

# Installation:

- `git clone https://github.com/Blacksuan19/Bootsplash-Themes.git`
- `cd manjaro-bootsplash-gnome`
- run `bootsplash-manjaro-amd.sh` to generate STL model.
- run `makepkg` to create Arch package and install it with `pacman -U $package_name`
- append `bootsplash-manjaro-amd` hook in the end of HOOKS string of `/etc/mkinitcpio.conf`
- add `quiet bootsplash.bootfile=bootsplash-themes/manjaro-amd/bootsplash` into `GRUB_CMDLINE_LINUX` string in `/etc/default/grub`
- run `sudo mkinitcpio -p linux415` (or linux416)
- run `sudo update-grub`
