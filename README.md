# EnvrSetup


## VirtualBox Setup
Shared folder between host and vm  
https://askubuntu.com/questions/22743/how-do-i-install-guest-additions-in-a-virtualbox-vm  
https://stackoverflow.com/questions/26740113/virtualbox-shared-folder-permissions



## Basic C/C++ Dev Environment Setup (Windows) without IDE
1. Install ubuntu bash from Microsoft Store
2. `sudo apt update`
3. `sudo apt install cmake' and `sudo apt install make'
4. `sudo apt install -y build-essential`  
Windows directory can be found in /mnt

## Killer Wireless/Bluetooth Setup (Ubuntu)
ath10k
AC-1535
wget http://mirrors.kernel.org/ubuntu/pool/main/l/linux-firmware/linux-firmware_1.169.3_all.deb  
sudo dpkg -i linux-firmware*.deb  
sudo modprobe -r ath10k_pci && sudo modprobe ath10k_pci
git clone git://git.kernel.org/pub/scm/linux/kernel/git/kvalo/ath.git

https://github.com/erikarn/alx
