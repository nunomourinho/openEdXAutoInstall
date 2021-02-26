# openEdXAutoInstall

First adapt the file config.yml to your cenario

Then, just clone the repo, upgrade, enter screen mode and then run bash install.sh on ubuntu 20.04 server.

In other words:

```bash
apt update
apt upgrade -y
apt install git screen -f -y
reboot
screen
git clone https://github.com/nunomourinho/openEdXAutoInstall.git
cd openEdXAutoInstall
bash install.sh
```
Now go drink a coffee, go lunch, go dinner. It will take really, really a loooong time :)
