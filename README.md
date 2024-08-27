Linux Networking Commands
1. ifconfig
- Display network interface information. Ifconfig
2. ip
- Show/manipulate routing, devices, policy routing, and tunnels. ip address show
3. route
- Display or manipulate the IP routing table. route -n
4. ping
- Send ICMP ECHO_REQUEST to network hosts. ping google.com
5. traceroute
- Print the route packets trace to network host. traceroute google.com
6. netstat
- Print network connections, routing tables, interface statistics, masquerade connections, and multicast memberships. netstat -an
7. ss
- Display socket statistics. ss -tulpn
8. hostname
- Show or set the system's host name. Hostname
9. dig
- DNS lookup utility. dig google.com
10. nslookup
- Query Internet name servers interactively. nslookup google.com
11. route
- Manipulate routing tables. route add default gw 192.168.1.1
12. iptables
- Administration tool for IPv4 packet filtering and NAT. iptables -L
13. tcpdump
- Dump traffic on a network. tcpdump -i eth0
14. sshd
- OpenSSH daemon. service sshd restart
15. telnet
- User interface to the TELNET protocol. telnet google.com 80
16. scp
- Secure copy (remote file copy program). scp file.txt user@remote:/path/to/destination
17. wget
- Non-interactive network downloader. wget http://example.com/file.zip
18. curl
- Command line tool for transferring data with URL syntax. curl http://example.com/api
19. iptraf
- Interactive color IP LAN monitor. Iptraf
20. iftop
- Display bandwidth usage on an interface. Iftop
21. nmap
- Network exploration tool and security scanner. nmap -sP 192.168.1.0/24
22. lsof
- List open files. lsof -i :80
23. ethtool
- Display or change ethernet card settings. ethtool eth0
24. arp
- Display or modify the ARP cache. arp -a
25. route
- Display or modify the IP routing table. Route
26. ss
- Display socket statistics. ss -s
27. hostnamectl
- Control the system hostname and related settings. hostnamectl status
28. resolvconf
- Manage DNS information. resolvconf -u
29. mtr
- Network diagnostic tool. mtr google.com
30. iwconfig
- Configure a wireless network interface. Iwconfig
31. nc
- Arbitrary TCP and UDP connections and listens. nc -l 8080
32. scp
- Copy files between hosts on a network. scp file.txt user@host:/path/to/destination
33. ssh-keygen
- Generate, manage, and convert authentication keys for ssh. ssh-keygen -t rsa
34. ss
- Show socket statistics. ss -t -a
35. tcpdump
- Capture and display packets on a network. tcpdump -i eth0 tcp port 80
36. route
- Add a new route. route add -net 192.168.2.0 netmask 255.255.255.0 gw 192.168.1.1
37. nmcli
- Command-line client for NetworkManager. nmcli connection show
38. dig
- Perform DNS lookups. dig +short A google.com
39. nload
- Visual representation of incoming and outgoing traffic. Nload
40. iperf
- Tool for measuring TCP and UDP bandwidth performance. iperf -c server_ip
41. fping
- Quickly ping multiple hosts. fping -a -g 192.168.1.1 192.168.1.254
42. iftop
- Real-time console-based network bandwidth monitoring tool. iftop -n
43. route
- Delete a route. route del -net 192.168.2.0 netmask 255.255.255.0
44. tcpdump
- Capture and display packets in ASCII. tcpdump -A -i eth0
45. netcat
- Utility for reading from and writing to network connections. nc -zv 192.168.1.1 22
46. nmtui
- Text User Interface for controlling NetworkManager. Nmtui
47. ethtool
- Change the speed/duplex settings of an Ethernet device. ethtool -s eth0 speed 100 duplex full
48. ss
- Show listening sockets. ss -l
49. host
- DNS lookup utility. host google.com
50. nmcli
- List available Wi-Fi networks. nmcli device wifi list
These commands cover a wide range of networking tasks and can be useful for troubleshooting, monitoring, and managing network configurations in a DevOps environment.
