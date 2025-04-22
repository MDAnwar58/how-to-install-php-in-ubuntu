# How to install php in ubuntu
###🟢 To install the latest stable PHP version (8.3) on Ubuntu:

Use the Ondřej Surý PPA (the most trusted source for PHP on Ubuntu):
```
sudo apt update
sudo apt install -y software-properties-common
sudo add-apt-repository ppa:ondrej/php
sudo apt update
sudo apt install -y php8.3
```
To install common extensions:
```
sudo apt install -y php8.3-cli php8.3-fpm php8.3-mysql php8.3-xml php8.3-mbstring php8.3-curl php8.3-zip php8.3-bcmath
```
