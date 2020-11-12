# Development environment setup
This repository is a collection of useful steps to set up a development environment on a new arch based linux system.


## Table of contents
- [Basic Setup](basic-setup)
- [NodeJS Installation](nodejs-installation)
- [PHP Installation](php-installation)
- [Composer Installation](composer-installation)
- [Angular Installation](angular-installation)

### Basic Setup
```
sudo pacman -S base-devel
```

### NodeJS Installation

```
sudo pacman -S nodejs
```

### PHP Installation
```
sudo pacman -S php
```
```
sudo pacman -S php-gd
```
Edit php config, enable:
```
extension=gd
extension=iconv
```
```
sudo nano /etc/php/php.ini
```

### Composer Installation
```
sudo pacman -S composer
```

### Angular Installation
```
git clone https://aur.archlinux.org/angular-cli.git
```
```
makepkg -si
```
