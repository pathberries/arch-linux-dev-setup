# arch-linux-dev-setup
Here is the quick dev setup every developer needs on their Arch Linux - Manjaro

#### Update the system
``` $ sudo pacman -Syu ```
#### Install Git
``` $ sudo pacman -S git ``` <br />
``` $ git --version ```
#### Install Java 11
``` $ sudo pacman -S jre11-openjdk-headless jre11-openjdk jdk11-openjdk openjdk11-doc openjdk11-src ```
``` $ java --version ```

#### Install NodeJs
``` $ pacman -S nodejs npm ``` <br />
``` $ node --version ```
#### Install yay - AUR helper
```
git clone https://aur.archlinux.org/yay-git.git
cd yay-git
sudo makepkg -si
```
#### Install VSCode
``` yay -S visual-studio-code-bin ```
#### Install Google Chrome
``` yay -S google-chrome  ```
