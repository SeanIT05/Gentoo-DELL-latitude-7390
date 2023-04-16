# Gentoo-DELL-latitude-7390
### Gentoo kernel configuration and more for the DELL latitude-7390 laptop. (Touchscreen, Touchpad, Audio, etc.)


![](https://i.imgur.com/EmDJVFg.png)

---

> If you do end up using everything mentioned here please remember to always check official gentoo kernel configuartion for the software you want to use. This kernel and other config is meant to be maintained, and if you need changed and later on updated if you want to update your kernel. Try to learn as much as you can and use that knowledge to your advantage. Have fun :sunglasses: 

# Why?
- It uses proprietary drivers
- Doesn't work out of the box
- Requires (rather) advanced configuration in order to work
- It is a popular laptop and I simply want everyone (even beginners) to be able to enjoy gentoo to its fullest and not give up halway through because nothing works

# What I added
- At the time of making this I used gentoo-sources (6.1.19)
- iwlwifi support
- NVME support
- Touchpad support
- Touchscreen support
- Intel video driver support
- Specific device configuration (CPU, etc.)

# What I removed
> I am writing about this in order for you to know what you might want to turn back on in case you need it :slightly_smiling_face: 
- Bluetooth support (I don't bother setting up bluetooth, it is also a security vulnerability)
- SATA support (The laptop uses NVME)
- Other FS support than EXT4
- ANY Microsoft support (WIP!)
- ANY Mac (Apple) support (WIP!)
- Android phone support
- LAN Support (I use wifi with NetworkManager)
- A LOT of bloat

# What I use

- [DWM](https://dwm.suckless.org/)
- [Alacritty](https://wiki.gentoo.org/wiki/Alacritty)
- [Slstatus](https://tools.suckless.org/slstatus/)
- [Pulseaudio](https://wiki.gentoo.org/wiki/PulseAudio)
- [Librewolf](https://librewolf.net/)
- [DMENU](https://tools.suckless.org/dmenu/)

Have a look at my config [here](https://github.com/seanit05/gentoo-setup) if you are interested!


### Sources
- https://wiki.gentoo.org/wiki/Dell_Latitude_7390
- https://wiki.gentoo.org/wiki/Iwlwifi
- https://wiki.gentoo.org/wiki/NetworkManager
- https://ark.intel.com/content/www/us/en/ark/products/124967/intel-core-i58250u-processor-6m-cache-up-to-3-40-ghz.html
- https://wiki.gentoo.org/wiki/Synaptics

---

# FAQ 
(nothing to see here yet)
