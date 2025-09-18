# 💻 Day 5 – Linux Commands: Networking, SSH & SCP

Today I continued my DevOps journey by practicing networking basics, connectivity testing, DNS queries, and secure remote access with SSH & SCP. 🚀

## ✅ What I learned & practiced:
- Networking Basics: `ip a`, `ifconfig`, `ping -c 4 google.com`, `traceroute google.com`, `curl -I https://google.com`, `wget`, `telnet`, `nslookup`, `netstat`, `mtr`, `dig`, `host`, `hostname`
- SSH: `ssh user@IP`, `ssh -p 2222 user@IP`, `ssh -i key.pem user@IP`, `ssh user@IP "hostname -I"`, `ssh-copy-id user@IP`
- SCP: `scp file.txt user@IP:/tmp/`, `scp user@IP:/tmp/file.txt .`, `scp -r mydir user@IP:/tmp/`, `scp -i key.pem file.txt user@IP:/home/user/`

## 📝 Tasks I completed:
1. Found my system IP address using `ip a`  
2. Tested connectivity to google.com with `ping -c 4 google.com` and saved the result into a file  
3. Fetched HTTP headers using `curl -I https://google.com`  
4. Queried DNS records using `nslookup`, `dig`, and `host`  
5. Traced routes with `traceroute` and `mtr`  
6. Installed and configured `openssh-server` and logged in via `ssh jp@127.0.0.1`  
7. Practiced secure file transfers with `scp`  

## 💡 Why it matters:
- Networking commands help troubleshoot connectivity, DNS issues, and server availability.  
- SSH provides secure remote access — the backbone of DevOps workflows.  
- SCP ensures quick and secure file transfers between systems.  


