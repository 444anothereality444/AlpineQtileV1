# AlpineQtile
install qtile on alpine linux

Enable /edge/* and /edge/testing @ /etc/apk/repositories. 
Then run "apk update", "apk upgrade".
Install xorg-server via "setup-xorg-base"
Install drivers, "apk search xf86-input*" (SYNAPTICS, EVDEV), "apk search xf86-video*" (AMDGPU)
Install dbus, "apk add dbus", "dbus-uuidgen >/var/lib/dbus/machine-id", "rc-update add dbus"
Then run "apk update", "apk upgrade".

Get git via apk.

git clone https://github.com/444anothereality444/AlpineQtileV1
cd AlpineQtileV1
doas chmod +x install.sh

##INSTALLING

Install dependencies by running "doas ash install.sh". The script will read required packages in dependencies.txt and creat .profile.
