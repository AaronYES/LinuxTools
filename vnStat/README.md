vnStat 2.6 config file

```
mv /etc/vnstat.conf /etc/vnstat.conf.old && wget https://raw.githubusercontent.com/AaronYES/LinuxTools/main/vnStat/vnstat.conf -O /etc/vnstat.conf && systemctl restart vnstat
```

The modified content is as follows

```
# try to detect interface maximum bandwidth, 0 = disable feature
# MaxBandwidth will be used as fallback value when enabled
BandwidthDetection 0

# maximum bandwidth (Mbit) for all interfaces, 0 = disable feature
# (unless interface specific limit is given)
MaxBandwidth 0

# how often (in seconds) interface data is updated
UpdateInterval 5

# how often (in minutes) data is saved to database
SaveInterval 1
```
