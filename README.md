RUN THIS COMMAND BEFORE RUNNING PROGRAM TO FORWARD PACKETS FROM ONE TARGET TO ANOTHER:

LINUX:
echo 1 >> /proc/sys/net/ipv4/ip_forward

MACOS:
sudo sysctl -w net.inet.ip.forwarding=1
