pkg update
pkg upgrade -y
pkg install git wget python python2 python3 proot-distro -y
git clone https://github.com/nedkely/kali-linux-termux.git
cd kali-linux-termux
chmod +x *
./install-kali.sh
