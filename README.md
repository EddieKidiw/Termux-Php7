# Termux-Php7
php 7.4.33 di termux

## installasi
Download file semua file deb yang sesuai dengan arsitektur termux masing-masing.
untuk mengetahui arsitekturnya ketikkan lalu enter

```bash
dpkg --print-architecture
```
    
setelah di download, install semuanya ( php_7.4.33-1_xxx.deb, php-apache_7.4.33-1_xxx.deb, php-fpm_7.4.33-1_xxx.deb, php-pgsql_7.4.33-1_xxx.deb )  xxx adalah arsitekturnya.

```bash
dpkg -i --force-all lokasi/filedebnya.deb
```
lalu
```bash
apt --fix-broken install -y
```
tunggu sampai selesai, cek php7 nya  
```bash
php7.4 -v
```
