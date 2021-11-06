# Brandon's Package List

Install packages after reinstalling OS

## Create List

### Create list from distributions package manager

`pacman -Qqen > packages.txt`

### Create list from AUR

`pacman -Qqem > aur-packages.txt`

## Usage

### Install packages from distribution

`sudo pacman -S --needed - < packages.txt`

### Install packages from AUR

`yay -S --needed - < aur_packages.txt`

