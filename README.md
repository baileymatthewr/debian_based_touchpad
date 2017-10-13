# debian_based_touchpad
If you use a debian-based linux distro or another that utilizes synaptics, then this will work for you.

## Debian / Ubunutu / LinuxMint / ArchLinux - Setup
Save this file in 

`/etc/X11/xorg.conf.d/`

The file should be named `50-synaptics.conf`

## Other Distros
You'll need to save this in some location where any user can get to it. Likely it is going to be in a similar path as listed above.
This is a configuration file, so it should be saved as 

`configuration_file_name.conf`

Perhaps even name the file `50-synaptics.conf` as stated above
