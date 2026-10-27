## Встановлення на Artix Linux

Потрібні `git` і `base-devel`:

```sh
sudo pacman -S --needed git base-devel

git clone https://github.com/SAM95-MEM95/asus-kbd-rgb.git
cd asus-kbd-rgb
makepkg -si
