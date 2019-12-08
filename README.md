# AntiScanIPList
Anti Ports Scanning IP/ISP List（Scanning Blacklist of friendly-civilized use Masscan/ZMap）

# Courtesy use of ZMap/Masscan tools
masscan -p 80 0.0.0.0/0 --excludefile IPBlacklist.list -oL result.out

zmap -p 80 -b IPBlacklist.list -o result.out
