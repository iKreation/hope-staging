Vagrant Development Machine
======================

Django runs with nginx with fastcgi. 

### Versions ( runs perfect with )
VirtualBox 4.3.2
Vagrant 1.3.5

### Emulates
webmoth.dec.uc.pt ( files in /var/www/cdn )
moth.dec.uc.pt ( files in /var/www/hope )
bdmoth.dec.uc.pt

### Services
- mysql
- mongodb
- php5-fpm
- fpm
- python-dev
...

### Address
192.168.56.101

### Install scripts in
/puphpet/files/exec-once

### Configuration files for services in
hope v0.1 - /var/www/hope/configurations/nginx/conf.d 
hope v0.1 - /var/www/hope/configurations/php5-fpm/php5

### Python dependencies list in
hope v0.1 - /var/www/hope/dependencies.txt

### Features
- Provisioned with puppet
- Install service dependencies
- Install all python dependencies
- Creates hope database
- Migrate and seed database with hope v0.1
