# usefull-shortcuts-and-commands
usefull shortcuts and commands for both windows and linux


# 🧠 Networking Commands Cheat Sheet (Linux vs Windows)

A quick reference guide comparing essential networking commands on **Linux** and **Windows** systems.

---

## 🔍 Check IP Address

| Task                | Linux                          | Windows              |
|---------------------|---------------------------------|----------------------|
| Show IP config      | `ip a` or `ifconfig`            | `ipconfig`           |
| Show routing table  | `ip route` or `route -n`        | `route print`        |

---

## 📶 Test Connectivity

| Task                | Linux                          | Windows              |
|---------------------|---------------------------------|----------------------|
| Ping a host         | `ping google.com`               | `ping google.com`    |
| Set ping count      | `ping -c 4 google.com`          | `ping -n 4 google.com` |

---

## 🌐 DNS Lookups

| Task                | Linux                          | Windows              |
|---------------------|---------------------------------|----------------------|
| Resolve domain      | `nslookup`                      | `nslookup`           |
| Detailed DNS info   | `dig google.com` *(dnsutils)*   | *Use `nslookup` only*|

---

## 📡 Trace Route

| Task                | Linux            | Windows           |
|---------------------|------------------|-------------------|
| Trace route         | `traceroute`     | `tracert`         |

---

## 🔌 Active Connections & Listening Ports

| Task                      | Linux                        | Windows                          |
|---------------------------|------------------------------|----------------------------------|
| Show open ports           | `netstat -tuln`              | `netstat -an`                    |
| With process IDs          | `netstat -tulnp`             | `netstat -ano`                   |
| Who owns port 80          | `lsof -i :80`                | `netstat -aon | find ":80"`      |

---

## 🧰 Other Useful Commands

| Task                              | Linux                              | Windows                                    |
|-----------------------------------|-------------------------------------|--------------------------------------------|
| Show ARP table                    | `arp -n`                            | `arp -a`                                   |
| Test HTTP response with `curl`    | `curl -I https://example.com`       | `curl` (if installed)                      |
| Show firewall rules               | `sudo iptables -L`                  | `netsh advfirewall show allprofiles`       |

---

## 📎 Notes
- Some Linux tools like `ifconfig`, `traceroute`, and `dig` may need to be installed manually using `apt`, `yum`, or `dnf`.
- Windows 10+ includes `curl` and `tar` by default.
- Use `Ctrl + C` to stop commands like `ping` in both systems.

---



