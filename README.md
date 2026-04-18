# Pocketchip-directions

After fixing sources

apt error apt-transport-https not found

sudo ln -s /usr/lib/apt/methods/http /usr/lib/apt/methods/https

Then

sudo apt-get clean
sudo rm -rf /var/lib/apt/lists/*
sudo apt-get update

Sudo apt-get upgrade
