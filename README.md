# Termux-Apktool
apktool for termux all deb
install package git
apt install git
download the apktool deb file
git clone https://github.com/1Tech-X/Termux-Apktool.git
then change directory to Termux-apktool
cd Termux-Apktool
Now install apktool 
dpkg -i apktool.deb

For decompile apk
apktool d Appname.apk

For Recompile
apktool b yourfolder/ --output out.apk

install package apksigner
apt install apksigner

sign apk with apksigner

apksigner -p yourpassword keystore yourapk newapkname



