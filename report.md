# The-role-of-VPNs-in-protecting-privacy
Understand the role of VPNs in protecting privacy and secure communication.

# 🛡️ Cyber Security Internship - Task 8  
## VPN Hands-On: Setup, Verify & Report

**Author:** [GOKUL KRISHNAN .S]  
**Date:** [04/11/2025]  

---

### 🎯 Objective  
To understand how a Virtual Private Network (VPN) secures data transmission, hides IP addresses, and affects network performance through hands-on setup and testing.

---

### 🧰 Tools Used  
- **VPN Provider:** Windscribe (Free)  
- **Protocol:** WireGuard (Port 443)  
- **Operating System:** Windows 11  
- **Websites Used:**  
  - IP Check: [whatsmyip.com](https://www.whatsmyip.com)  
  - Speed Test: [fast.com](https://fast.com)  

---

### 🔧 Step-by-Step Process  

1. **Downloaded & Installed VPN:**  
   Installed the official Windscribe Windows client from [https://windscribe.com](https://windscribe.com).  

2. **Login & Connect:**  
   Logged in using free account credentials and connected to the **Hong Kong – Victoria** server using the **WireGuard 443** protocol.  

3. **IP Verification:**  
   - **Without VPN:** IP → `115.99.xx.xx` (ISP-assigned)  
   - **With VPN:** IP → `146.70.xx.xx` (VPN server IP – Hong Kong)  
   ✅ The IP changed successfully, confirming that traffic was routed through the VPN.  

4. **DNS/IP Leak Test:**  
   - Verified using [https://ipleak.net](https://ipleak.net)  
   - ✅ **No DNS or IP leaks detected.**  
   All DNS queries resolved through Windscribe’s secure servers.  

5. **Speed Test Comparison:**  
   - **Without VPN:** 320 Mbps (normal speed)  
   - **With VPN:** 1.2 Mbps (VPN-connected speed)  
   ⚙️ The expected drop occurred due to encryption overhead and remote server distance.  

6. **Disconnection:**  
   - Disconnected VPN and confirmed IP reverted to the original ISP address.  

---

### 📊 **Results Summary**

| Test Type | IP Address | Server Location | Speed (Mbps) | Leak Status |
|------------|-------------|----------------|---------------|-------------|
| Without VPN | 115.99.xx.xx | Local ISP (India) | 320 | N/A |
| With VPN | 146.70.xx.xx | Hong Kong (Windscribe) | 1.2 | No leaks |

---

### 📸 **Screenshots Summary (in /screenshots folder)**  
- `VPN_connected.png` – Windscribe connected (Hong Kong server)  
- `IP_without_vpn.png` – Real IP before VPN (115.99.xx.xx)  
- `IP_with_vpn.png` – VPN IP (146.70.xx.xx)  
- `Speed_test_without_vpn.png` – 320 Mbps (normal speed)  
- `Speed_test_with_vpn.png` – 1.2 Mbps (VPN-connected speed)

---

### 🔍 **Observations**  
- The VPN successfully masked the real IP and routed traffic through Hong Kong.  
- No DNS/IP leaks were found, meaning the VPN tunnel was secure.  
- Speed decreased significantly due to encryption and routing overhead.  
- Free VPN servers are slower but effective for privacy testing.  

---

### 🧠 **Learning Outcomes**  
- Understood how VPN encryption and tunneling work.  
- Learned to verify IP and DNS leak protection.  
- Gained awareness of how encryption overhead affects internet speed.  
- Practiced documentation and security analysis for a basic network privacy tool.


---
### 📤 **Submission**
- **Repository Name:** `CyberSec-Task8-VPN-HandsOn`  
- **Files to Upload:**
  - `README.md`  
  - `report.md` (this file)  
  - `/screenshots/` folder with the five screenshots  
- **Submit repo link here:** [https://forms.gle/8Gm83s53KbyXs3Ne9](https://forms.gle/8Gm83s53KbyXs3Ne9)

---

**✅ Final Status:**  
VPN successfully configured, tested, verified for no leaks, and documented for submission.
