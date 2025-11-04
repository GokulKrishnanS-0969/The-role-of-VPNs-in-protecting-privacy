# The-role-of-VPNs-in-protecting-privacy
Understand the role of VPNs in protecting privacy and secure communication.

# 🛡️ Cyber Security Internship - Task 8  
## VPN Hands-On: Identify, Connect & Verify Secure VPN Usage  

---

### 🎯 Objective
To configure a free VPN client, verify secure data tunneling and IP masking, test for DNS/IP leaks, and analyze how VPN encryption impacts network performance.

---

### 🧰 Tools & Setup
- **VPN Used:** Windscribe (Free)  
- **Protocol:** WireGuard (Port 443)  
- **Operating System:** Windows 11  
- **Testing Websites:**
  - IP Check → [https://www.whatsmyip.com](https://www.whatsmyip.com)  
  - Speed Test → [https://fast.com](https://fast.com)  
  - DNS Leak Test → [https://ipleak.net](https://ipleak.net)

---

### 🔧 Implementation Steps
1. Installed the Windscribe VPN client from its official website.  
2. Logged in with a free account and connected to the **Hong Kong – Victoria** server.  
3. Verified IP change via *whatsmyip.com*:
   - Without VPN → `115.99.xx.xx`
   - With VPN → `146.70.xx.xx`
4. Confirmed **no DNS/IP leaks** through *ipleak.net*.  
5. Compared network speed:
   - Without VPN → **320 Mbps**
   - With VPN → **1.2 Mbps**  
6. Documented all findings and screenshots.

---

### 📊 Summary of Findings
| Condition | IP Address | Location | Speed (Mbps) | Leak Status |
|------------|-------------|-----------|---------------|-------------|
| Without VPN | 115.99.xx.xx | Local ISP (India) | 320 | N/A |
| With VPN | 146.70.xx.xx | Hong Kong (Windscribe) | 1.2 | No leaks |

---

### 📸 Screenshots (in `/screenshots` folder)
- `VPN_connected.png` – Windscribe connected (Hong Kong server)  
- `IP_without_vpn.png` – Real IP before connection  
- `IP_with_vpn.png` – Masked IP after connection  
- `Speed_test_without_vpn.png` – Normal connection speed  
- `Speed_test_with_vpn.png` – VPN connection speed  

---

### 🧠 Key Learnings
- Practical understanding of VPN encryption and tunneling.  
- Learned how to verify IP masking and DNS leak protection.  
- Observed encryption overhead and performance trade-offs.  
- Strengthened awareness of online privacy and secure browsing practices.

---

### 👤 Author
**Name:** [GOKUL KRISHNAN .S]  
**Internship:** Cyber Security Internship  
**Task:** 8 – VPN Hands-On  
**Date:** [04/11/2025]

---

✅ *Task 8 completed successfully — VPN configured, verified, and documented.*
