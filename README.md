pkg update;

pkg upgrade -y;

pkg install git wget curl;

pkg install python python2 python3;

okg install proot-distro;

git clone https://github.com/nedkely/kali-linux-termux.git

ls
cd kali-linux-termux

chmod +x *

./install-kali-linux-nedkely.sh



_-------------------------------
termux-setup-storage
pkg install wget
wget -O install-nethunter-termux https://offs.ec/2MceZWr
chmod +x install-nethunter-termux
./install-nethunter-termux
