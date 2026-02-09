Linux Networking Commands
🔹 1. ip (Used to configure and view network interfaces, IP addresses, and routes.)
```
ip addr
ip link
ip route
```
Common Usage
| Command                 | Description             |
| ----------------------- | ----------------------- |
| `ip addr show`          | Show IP addresses       |
| `ip link show`          | Show network interfaces |
| `ip route show`         | Show routing table      |
| `ip link set eth0 up`   | Enable interface        |
| `ip link set eth0 down` | Disable interface       |

2. ifconfig(Used to configure network interfaces (deprecated, replaced by ip).
```
ifconfig
```
| Command              | Description       |
| -------------------- | ----------------- |
| `ifconfig`           | Show interfaces   |
| `ifconfig eth0 up`   | Enable interface  |
| `ifconfig eth0 down` | Disable interface |

🔹 3. ping(Used to check network connectivity between hosts.)
```
ping google.com
```
| Option | Purpose               |
| ------ | --------------------- |
| `-c 4` | Send 4 packets        |
| `-i 2` | Interval of 2 seconds |

🔹 4. netstat (Used to display network connections, ports, routing tables.)
```
netstat -tulnp
```
| Option | Meaning   |
| ------ | --------- |
| `-t`   | TCP       |
| `-u`   | UDP       |
| `-l`   | Listening |
| `-n`   | Numeric   |
| `-p`   | PID       |

🔹 5. ss (Modern Replacement of netstat Faster and more powerful.)
```
ss -tulnp
```
| Command    | Description     |
| ---------- | --------------- |
| `ss -tuln` | Listening ports |
| `ss -s`    | Socket summary  |

🔹 6. traceroute(Shows the path packets take to reach a destination.)
```
traceroute google.com
```
🔹 7. nslookup(Used for DNS lookup.)
```
nslookup google.com
```

🔹 8. dig (Advanced DNS Tool)
```
dig google.com
```
| Use                     | Purpose      |
| ----------------------- | ------------ |
| `dig google.com`        | DNS record   |
| `dig google.com +short` | Short output |

🔹 9. hostname(Shows or sets system hostname.)
```
hostname
hostname -I
```
| Command       | Description |
| ------------- | ----------- |
| `hostname`    | System name |
| `hostname -I` | IP address  |

🔹 10. curl(Used to test APIs and HTTP/HTTPS connectivity.)
```
curl http://example.com
```

🔹 11. wget(Used to download files from the internet.)
```
wget http://example.com/file.zip
```

🔹 12. arp(Displays ARP table (IP → MAC mapping).
```
arp -a
```

🔹 13. route (Used to view routing table.)
```
route -n
```
(Modern alternative: ip route)

🔹 14. nmap(Used for network scanning & port scanning.)
```
nmap localhost
```

15. tcpdump(Used for packet capture & analysis.)
```
tcpdump -i eth0
```

📊 Most Important Commands (Interview Focus)
| Purpose           | Command           |
| ----------------- | ----------------- |
| Check IP          | `ip addr`         |
| Test connectivity | `ping`            |
| Check open ports  | `ss -tulnp`       |
| DNS lookup        | `nslookup`, `dig` |
| Download          | `wget`, `curl`    |
| Routing           | `ip route`        |
