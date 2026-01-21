# 🛡️ Snort IDS: Deployment, Configuration & Attack Testing

![Category](https://img.shields.io/badge/Category-Network%20Security-blue.svg)
![Tool](https://img.shields.io/badge/Tool-Snort-orange.svg)
![OS](https://img.shields.io/badge/OS-Ubuntu-E95420.svg)
![Security](https://img.shields.io/badge/Type-IDS/IPS-red.svg)

> **BobXploit Security Labs 🛡️**
> Successfully installed and configured **Snort IDS** on Ubuntu to monitor, detect, and log network intrusion attempts in real-time. This project validates defensive capabilities against live attack simulations.

---

## 📺 Project Demonstration (YouTube)
Check out the full walkthrough and live attack detection on my YouTube channel:
[<img alt="Snort IDS: Deployment, Configuration Attack Testing" width="100%" src="https://github.com/tech2etc/Youtube-Tutorials/blob/main/Build%20and%20Deploy%20Ecommerce%20Website%20With%20HTML%20CSS%20JavaScript%20Full%20Responsive%20Ecommerce%20Course%20FREE.PNG?raw=true" />](https://youtu.be/89Mq2-fk6jM?si=wsYWCoHMxinK6m0u)

[![Snort IDS Project YouTube](https://img.shields.io/badge/YouTube-Watch%20Video-red?style=for-the-badge&logo=youtube)](https://youtu.be/89Mq2-fk6jM?si=wsYWCoHMxinK6m0u)

---

## 🚀 Key Achievements
* 🏗️ **IDS Deployment:** Installed and optimized Snort on an Ubuntu environment.
* ✍️ **Custom Rules:** Configured detection rules to identify specific malicious traffic patterns.
* 🔴 **Live Attack Simulation:** Used **Metasploit** to launch exploits and test IDS responsiveness.
* 📊 **Traffic Logging:** Real-time monitoring and logging of intrusion attempts for forensic analysis.
* 🛡️ **Defensive Validation:** Verified the detection of common exploits and port scans.

---

## 🧰 Technologies & Tools
| Category | Tool |
| :--- | :--- |
| **IDS Engine** | Snort |
| **System OS** | Ubuntu Linux |
| **Attack Framework** | Metasploit Framework |
| **Traffic Generation** | Nmap / Custom Scripts |
| **Analysis** | Snort Logs & Alerts |

---

## 🛠️ Implementation Workflow

### 1️⃣ Snort Installation & Config
Setting up the environment and configuring the network variables:
```bash
# Update and install Snort
sudo apt-get update
sudo apt-get install snort -y

# Verify configuration
snort -T -c /etc/snort/snort.conf

