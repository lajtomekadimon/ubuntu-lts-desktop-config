# Lajto's Ubuntu LTS desktop config
My personal configuration for Ubuntu LTS in desktop.

After updating and configuring graphics, run:

```sh
sudo apt install git make

git clone https://github.com/lajtomekadimon/ubuntu-lts-desktop-config
cd ubuntu-desktop-config

make -s configure
make -s programming
make -s telegram

cd ..
rm -Rf ubuntu-desktop-config
```

Install fonts from files.

Reboot (select gnome-shell in GDM), and after that, install manually:

- VS Code (sync config)

Configure Firefox properly and change this in `about:config`:

- Set `extensions.pocket.enabled` to `false`.
- Set `middlemouse.paste` to `false`.
- Create new String value called `widget.content.gtk-theme-override`: `Adwaita`.

Configure these programs:

- GNOME
- GNOME Tweaks
- GNOME Terminal
- GNOME Disks
- Gedit
- Nautilus
- Rhythmbox
- Transmission
- Telegram Desktop
- LibreOffice

Reboot, and ready to go!