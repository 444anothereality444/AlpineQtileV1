# AlpineQtile
install qtile on alpine linux

Enable /edge/* and /edge/testing @ /etc/apk/repositories. 
Then run "apk update", "apk upgrade".
Install edge kernel with "apk add linux-edge" and remove the older.
Then run "apk update", "apk upgrade".
Install xorg-server via "setup-xorg-base"
Run "setup-devd"
Then run "apk update", "apk upgrade".

Get git via apk.

git clone https://github/444anothereality444.com/AlpineQtileV1
cd AlpineQtileV1
doas chmod +x install.sh

##INSTALLING

Install dependencies by running "doas ash install.sh". The script will read required packages in dependencies.txt and creat .profile.
