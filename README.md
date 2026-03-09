## 🎯 Objective
Identify the Metasploitable 2 machine within the local network using basic discovery tools.

---

## 🛠️ Tools Used
- Netdiscover  
- Nmap (Ping Scan)

---

## 📌 Steps (General & Safe)
1. Run a network discovery tool to detect active hosts.
2. Identify the IP address assigned to Metasploitable 2.
3. Confirm the machine is reachable within the same subnet.

---

## 📈 Results
- A Linux-based host was detected.
- It appeared with an IP address similar to:

- ## 🎯 Objective
Identify open ports and active services running on the Metasploitable 2 machine.

---

## 🛠️ Tools Used
- Nmap (Port Scanning)

---

## 📌 Steps (Safe & High-Level)
1. Perform a general port scan.
2. Document all open ports.
3. Identify the protocols used (TCP/UDP).

---

## 📈 Results (Common in Metasploitable 2)
- Port 21: FTP  
- Port 22: SSH  
- Port 23: Telnet  
- Port 25: SMTP  
- Port 80: HTTP  
- Database-related ports  
- Legacy service ports

---

## 🧠 Analysis
- The large number of open ports indicates a training environment.
- Many services are intentionally outdated for learning purposes

- ## 🎯 Objective
Analyze the services running on open ports and understand their security implications.

---

## 🛠️ Tools Used
- Nmap Service Detection  
- Banner Grabbing

---

## 📌 Example Services
- FTP: File Transfer  
- SSH: Secure remote access  
- Telnet: Legacy unencrypted protocol  
- HTTP: Web server  
- SMTP: Email sending service  

---

## 🧠 Analysis
- Legacy services like Telnet highlight common security weaknesses.
- Service analysis helps understand potential risks in real environments.
- # 🎯 Objective
Collect general banner information from services to identify software versions.

---

## 📌 Example Information
- Web server version  
- FTP version  
- Operating system hints  
- General service details  

---

## 🧠 Analysis
- Version information helps understand potential risks (theoretical only).
- Banner grabbing is a core part of reconnaissance

Objective
Analyze WHOIS and DNS information (if applicable) to understand domain structure.

---

## 📌 Analysis Includes
- Domain registration details  
- Country  
- Registrar  
- DNS records such as:
  - A Record  
  - MX Record  
  - NS Record  

---

## 🧠 Analysis
- These details help understand system architecture.
- Metasploitable usually has no domain, but the exercise is valuable for learning.
