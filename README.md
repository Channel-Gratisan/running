## Installation 
## 1.
Part 1: Update dan Upgrade
   <img src="https://img.shields.io/badge/Update%20Upgrade-green"> 
  ```html
apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot
```

### 2.
Part 2: Install Semua Layanan VPN /Install All VPN Service
  <img src="https://img.shields.io/badge/Install_Semua_Layanan_VPN%20Batch-green">
  ```html
rm -f setup.sh && apt update && apt upgrade -y && update-grub && sleep 2 && apt-get update -y && apt-get upgrade && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/Channel-Gratisan/scfull/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
```
