# chip-notes

Some notes on for setting up https://nextthing.co/pages/chip

# boot logs
Use serial connection with top 3 inside pins nearest micro-usb connector: GND, TX, RX

# basic preparation
```sh
sudo nmcli device wifi connect $SSID password $PASSWORD
sudo apt-get update &&\
sudo apt-get dist-upgrade -y&&\
sudo apt-get install tmux vim -y&&\
sudo dpkg-reconfigure tzdata
```

# motion setup
```sh
sudo apt-get install motion
sudo vi /etc/motion/motion.conf
sudo vi /etc/default/motion
```
