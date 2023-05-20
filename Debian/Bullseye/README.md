Replace Debian 11 full source
```
mv /etc/apt/sources.list /etc/apt/sources.list.old && wget https://raw.githubusercontent.com/AaronYES/LinuxTools/main/Debian/Bullseye/sources.list -O /etc/apt/sources.list && apt update -y
```
