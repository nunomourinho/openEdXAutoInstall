# openEdXAutoInstall

Just clone the repo, upgrade, enter screen mode and then run bash install.sh on ubuntu 20.04 server.

In other words:

```bash
apt update
apt upgrade -y
apt install git screen -f -y
reboot
git clone https://github.com/nunomourinho/openEdXAutoInstall.git
cd openEdXAutoInstall
bash install.sh
```
