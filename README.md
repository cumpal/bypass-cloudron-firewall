# bypass-cloudron-firewall
Allows all ports 1-65535 UDP+TCP to go through Cloudrons firewall


1. Drop ports.json under /home/yellowtent/boxdata/firewall/ (if firewall folder doesn't exist make it)
2. (sudo) systemctl restart cloudron-firewall
3. profit
