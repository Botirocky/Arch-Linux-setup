# ArchLinux setup
All documentation was [here](https://archlinux.org/)

## Basic app's
```bash
sudo pacman -S firefox nano discord git vim nvim nmap tor rpi-imager qflipper fish ghostty kvantum john htop wpscan btop macchina fastfetch uwufetch lsd virtualbox reflector networkmanager cava cmatrix cowsay dua-cli felix-rs kitty wine aalib satty
```
- I think these app's are good for beginner's.

## YAY installation
```bash
git clone https://aur.archlinux.org/yay.git
```
- YAY is an [AUR](https://aur.archlinux.org/) downloader.

## Fun app's 
![Névtelen1](https://github.com/user-attachments/assets/d9176caf-9c56-44bc-8609-7698162833af)

## Enble Network Manager
```bash
sudo systemctl enable NetworkManager.service 
sudo systemctl start NetworkManager.service 
```
<img width="2008" height="391" alt="Névtelen" src="https://github.com/user-attachments/assets/bf557da0-b245-426b-b4a6-405eb83f647f" />
sudo systemctl enable NetworkManager.service 
sudo systemctl start NetworkManager.service 
## Set WI-FI with iwctl
- Where it says "DEVICE", write the name of your device. Where it says "SSID", write your WI-FI SSID.
  
```bash
iwctl
```
```bash
device list
```
```bash
station DEVICE scan
```
```bash
station DEVICE get-networks
```
```bash
station DEVICE connect SSID
```
```bash
quit
```
## Disable
```bash
sudo systemctl disable NetworkManager.service 
sudo systemctl stop NetworkManager.service 
```
## Bash setup
```bash
bash -c "$(curl -fsSL https://raw.githubusercontent.com/ohmybash/oh-my-bash/master/tools/install.sh)"
```
## Setup for konsole
```bash
sudo nano ~/. bashrc
```
- Write Fastfetch or Pokego after
- Use:
```bash
pokego --random 1 --no-title
```
## Setup for pacman
```bash
sudo nano /etc/pacman.conf
```
- #Color (take down #)
- line and ILoveCandy

# More setup information coming soon..
