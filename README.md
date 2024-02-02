# AlpineQtileV1
install qtile on alpine linux

Install xorg-server via "setup-xorg-base"
Run "setup-devd"
Enable community/edge @ /etc/apk/repositories. 
Then run "apk update", "apk upgrade".
Get git via apk.

git clone https://github/444anothereality444.com/AlpineQtileV1
cd AlpineQtileV1
doas chmod +x install.sh

##INSTALLING

Install dependencies by running "doas ash install.sh". The script will read required packages in dependencies.txt.
