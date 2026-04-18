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
