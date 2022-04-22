# My theoretical OS concept
This concept is a mix of great, already-existing tools and concept tools that do better than current tools.
## System Base
* Based on openSUSE MicroOS
* XanMod edge default kernel, XanMod stable as backup
## Modern Desktop Technologies
* Wayland, X11 available as backup
* Pipewire (WirePlumber), PulseAudio available as backup
* Flatpak used for all non-essential apps
* Flathub enabled out of the box
## Desktop Environment Configuration
* Custom Qt-based lightweight DE
* HIG: Common options first with advanced hidden (burger menu), simple, flat, rounded, buttons in header bar,
* Custom simple, rounded, flat theme
* Papirus icon theme with tweaks
* Custom Plymouth boot screen with logo
* Fork of SDDM with theme based on Chili
* Clock widget
* Curated custom wallpapers
## Default Apps
* MauiKit core apps
* Librewolf with Orchis theme
* ONLYOFFICE
## Installation
* rEFInd bootloader
* default option uses proprietary drivers if their hardware is detected
* option to boot without proprietary drivers
* ISO same as final install
* Calamares fork as installer - better looks
* Encrypted by default
* Import some preferences/data/configs from other os partition?
* Secure Boot enabled
* Proprietary drivers installed by default, option to install proprietary codecs and fonts