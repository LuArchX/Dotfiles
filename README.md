# Manjaro + i3 rice
 My first Linux rice, pastel colors and a bit of transparency

 ![manjaroi3](https://i.imgur.com/PdfXIW5.png)

 # Installation

 Dependencies :
 
`base-devel libuv cairo xcb-util-image xcb-util-wm xcb-util-xrm xcb-util-cursor alsa-lib libpulse libmpdclient libnl jsoncpp curl hicolor-icon-theme libconfig libdbus libev libgl pcre pixman xcb-util-renderutil python3 freetype2 fontconfig wayland libx11 libxkbcommon-x11 libxi dbus lcms2 librsync xxhash kitty-terminfo kitty-shell-integration picom polybar kitty`

 ```fish
sudo pacman -S base-devel libuv cairo xcb-util-image xcb-util-wm xcb-util-xrm xcb-util-cursor alsa-lib libpulse libmpdclient libnl jsoncpp curl hicolor-icon-theme libconfig libdbus libev libgl pcre pixman xcb-util-renderutil python3 freetype2 fontconfig wayland libx11 libxkbcommon-x11 libxi dbus lcms2 librsync xxhash kitty-terminfo kitty-shell-integration picom polybar kitty
```


``` fish
git clone https://github.com/LuArchX/Dotfiles.git
cd Dotfile
```
I highly recommend saving your initial configuration files. You can use the backup script.
```
./backup_script
```

Afterwards, replace or edit your configuration files: picom.conf, Polybar (modules, colors...), and Kitty.

Don't forget to replace the name of your interface in `polybar/modules.ini`, under the `[module/network]` section, with your own. You can use the following command to display it :

```bash
iwconfig
```
example :

```
interface_name     XXXX XX.XX  XXXX:XXXXXX  XXXXXXXX: XX:XX:XX:XX:XX:XX
          XX XXXX=XX Mb/s   XX-XXXXX=XX dBm
          XXXX XXXXX XXXX:XX   XX:XXX   XXXXXXXXX:XXX   XXXXXXXXXXXX
          XXXXXXXXXXXXXXXX/XX  XXXXXXXXXXXX:XX
          XXXXXXXXXX=XX/XX   XXXXXXXX:XX/XX  XXXX XXXX:XX
          XXXX XXXXXXXXX=XX/XX  XXXXXXXX:XX/XX
```

# Color Theme

[Cattppucin](https://github.com/catppuccin)
