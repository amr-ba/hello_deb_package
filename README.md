# hello_deb_package
hello debian package test

## how to uild : 
dpkg-buildpackage -us -uc -d

## how to install : 
sudo dpkg -i ../hello_2.10-3_amd64.deb

## How to remove : 
sudo dpkg --remove hello


