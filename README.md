# notes

# use tcpdump to act as syslog server
sudo tcpdump -lns 0 -w - udp and port 514 | strings
