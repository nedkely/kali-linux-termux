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
