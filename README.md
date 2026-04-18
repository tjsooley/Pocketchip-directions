# Pocketchip-directions

After fixing sources

apt error apt-transport-https not found 
 1) sudo apt-get clean
  2) sudo ln -s /usr/lib/apt/methods/http /usr/lib/apt/methods/https
  3) sudo apt-get update
  4) sudo apt-get install apt-transport-https ca-certificates

Cleaning apt cache

  1) sudo apt-get clean
  2) sudo rm -rf /var/lib/apt/lists/*
  3) sudo apt-get update

VNC & SSH
sudo apt-get install ssh

VNC
1) sudo apt-get install x11vnc
2) x11vnc -storepasswd
Store this in ~/.vnc/passwd if prompted.
3) x11vnc -forever -usepw -display :0
4) sudo nano ~/.bashrc
  4a) goto bottom
    4b)hit enter 2 times
5) Past x11vnc -forever -usepw -display :0
