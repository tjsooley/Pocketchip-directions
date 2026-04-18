# Pocketchip-directions

After fixing sources

apt error apt-transport-https not found (Line 7, 8, 9)
sudo apt-get clean
sudo ln -s /usr/lib/apt/methods/http /usr/lib/apt/methods/https
sudo apt-get update
sudo apt-get install apt-transport-https ca-certificates

Then

sudo apt-get clean
sudo rm -rf /var/lib/apt/lists/*
sudo apt-get update

Sudo apt-get upgrade
