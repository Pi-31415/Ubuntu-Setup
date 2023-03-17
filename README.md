# Ubuntu-Setup
A list of requirements for ubuntu 18.01 setup for Robotics

**IMPORTANT: Set-up ROS first. Then do other stuff**

## Essential Apps

Install Chrome and login first

```
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb

sudo apt install ./google-chrome-stable_current_amd64.deb
```

Then get Brave

```
sudo apt install apt-transport-https curl

sudo curl -fsSLo /usr/share/keyrings/brave-browser-archive-keyring.gpg https://brave-browser-apt-release.s3.brave.com/brave-browser-archive-keyring.gpg

echo "deb [signed-by=/usr/share/keyrings/brave-browser-archive-keyring.gpg arch=amd64] https://brave-browser-apt-release.s3.brave.com/ stable main"|sudo tee /etc/apt/sources.list.d/brave-browser-release.list

sudo apt update

sudo apt install brave-browser

```

Teamviewer
(https://www.teamviewer.com/en/download/linux/)


Install Ulauncher as spotlight. Download at (https://github.com/Ulauncher/Ulauncher/releases/download/5.11.0/ulauncher_5.11.0_all.deb)


## Drivers Setup
Snd HDA (from own repo) for Sound
Camera
Chinese Keyboard

Expressvpn

## Terminal Setup
- Node and npm (https://askubuntu.com/questions/1088662/npm-depends-node-gyp-0-10-9-but-it-is-not-going-to-be-installed#1092849)
- Python2 and Python3 and pip
- Flutter
- Yarn
- No zsh
- Hexedit

## GUI Setup (Finally and Themes)
See the screenshots in folder

## Cool Fonts

- Oxanium
- Neuropol X
- Adobo (https://www.dafont.com/adobo.font)
- Earth Orbiter (https://www.dafont.com/earth-orbiter.font)
- Potra (https://www.dafont.com/potra.font)
https://www.dafont.com/varino.font

## Themes

- https://github.com/vinceliuice/WhiteSur-gtk-theme
- https://github.com/yeyushengfan258/Reversal-icon-theme
- https://github.com/ful1e5/Bibata_Cursor


White Sur theme installations 
 ```
 sudo ./install.sh -c "Dark" -o "normal" -N "glassy" --name "K.A.G.U.Y.A" -s 280 -i "ubuntu" -m -HD --round --darker --nord -b "/home/pi/Documents/GitHub/Prion-Theme/TealGradedChineseBlur.jpg"
  ```
  
  Setup Background for login
  
  https://www.omgubuntu.co.uk/2022/01/change-ubuntu-login-screen-background


Note to self : Also set up the hosts file (in your other repo).
