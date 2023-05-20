自用 vnStat 配置

修改内容
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
