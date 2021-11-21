# snort install on ubuntu
sudo apt-get update && sudo apt install git -y  &&  cd ~/

git clone https://github.com/NMT99/snort.git

cd snort && sudo chmod +x install && ./install
