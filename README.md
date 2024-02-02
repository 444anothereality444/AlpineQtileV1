# AlpineQtileV1
install qtile on alpine linux

First step, enable community/edge @ /etc/apk/repositories. 
You need edge kernel : "apk add linux-edge", for stability, delete your old kernel. 
Then run "apk update", "apk upgrade".
Get git via apk.

git clone https://github/444anothereality444/AlpineQtileV1
cd AlpineQtileV1

##INSTALLING

Install dependencies by running ./install.sh. The script will read required packages in dependencies.txt.
