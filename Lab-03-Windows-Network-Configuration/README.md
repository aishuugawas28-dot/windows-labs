#  Lab 03 - Windows Network Configuration & Troubleshooting

##  Objective

Learn basic Windows networking commands and understand how to troubleshoot network connectivity using Command Prompt.

---

##  Environment

- Operating System: Windows 11 Pro
- Platform: Oracle VirtualBox
- Command Prompt

---

##  Commands Performed

### Display Computer Name

```cmd
hostname
```

### Display IP Configuration

```cmd
ipconfig
```

### Display Complete Network Information

```cmd
ipconfig /all
```

### Display MAC Address

```cmd
getmac
```

### Test Internet Connectivity

```cmd
ping google.com
```

### Test Local TCP/IP Stack

```cmd
ping 127.0.0.1
```

### Test Connectivity Using Google DNS

```cmd
ping 8.8.8.8
```

### DNS Lookup

```cmd
nslookup google.com
```

### Trace Route

```cmd
tracert google.com
```

### Display ARP Table

```cmd
arp -a
```

### Display Routing Table

```cmd
route print
```

### Display Active Network Connections

```cmd
netstat -ano
```

---

##  Screenshots

All screenshots are available inside the `screenshots` folder.

---

##  What I Learned

- How to identify system hostname
- How to view IP configuration
- How DNS resolution works
- How to verify Internet connectivity
- How to trace packet routes
- How ARP maps IP addresses to MAC addresses
- How to view the Windows routing table
- How to monitor active network connections

---

##  Real-World Use Cases

- Troubleshooting network connectivity
- Diagnosing DNS issues
- Checking gateway configuration
- Identifying network adapters
- Monitoring active TCP/UDP connections
- Basic IT Support troubleshooting

---

#  Lab Status

**Completed Successfully**
