# ThePizzaDude/ip-geolocator @ GitHub.com
This is a VERY slightly modified verion of [@KyxRecon](https://github.com/KyxRecon "View profile")'s IP geolocation tool. I made it for my convenience but I figured I'd put it on my basically empty GitHub.

## installation on Linux
### Debian Family (and ubuntu):
```bash
sudo apt-get install perl git
git clone https://github.com/ThePizzaDude/ip-geolocator.git
cd ip-geolocator
mv ip-geolocator.pl ~/ipgeo.pl
```
For other distros:
### Arch:
```bash
pacman -Sy perl git
git clone https://github.com/ThePizzaDude/ip-geolocator.git
cd ip-geolocator
mv ip-geolocator.pl ~/ipgeo.pl
```
### CentOS: 
```bash
yum install perl git
git clone https://github.com/ThePizzaDude/ip-geolocator.git
cd ip-geolocator
mv ip-geolocator.pl ~/ipgeo.pl
```

add the following line to your `~/.bashrc`
```
alias ipl='perl ~/ipgeo.pl'
```
### Isn't listed
it's pretty much the same thing, just perform the equivalent of apt-get install perl git with whatever package manager you use.


#### On anything else
i don't know or care lol
