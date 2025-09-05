# Final-L-T
# 🛰️ Applied Industrial Internet of Things  
## Configuration of Address Resolution Protocol (ARP) using Cisco Packet Tracer  

---

## 📌 Aim
To construct a Local Area Network (LAN) and demonstrate the operation of Address Resolution Protocol (ARP) using Cisco Packet Tracer.

---

## 📌 Problem Statement
In LAN communication, devices use IP addresses for logical identification but rely on MAC addresses for data transmission. Address Resolution Protocol (ARP) is required to resolve IP addresses into MAC addresses. The objective of this project is to simulate a LAN, configure devices, and observe ARP request/reply operation.

---

## 📌 Scope
- Demonstrates ARP request and reply in a LAN.  
- Helps understand IP-to-MAC address resolution.  
- Useful for IoT and Industrial networking applications.  
- Provides practical skills in using Cisco Packet Tracer for simulation.  

---

## 📌 Components Used
### **Software**
- Cisco Packet Tracer (IDE for network simulation)

### **Networking Devices**
- 3 × PCs (PC-PT)  
- 1 × Switch (2960-24TT or 8-port switch)  
- Copper Straight-Through Cables (to connect PCs to Switch)  

---

## 📌 Procedure
1. Connect PCs to the Switch using Copper Straight-Through Cables.  
   - PC0 → Switch Fa0/1  
   - PC1 → Switch Fa0/2  
   - PC2 → Switch Fa0/3  

2. Configure IP addresses:  
   - PC0 → `192.168.1.1 / 255.255.255.0`  
   - PC1 → `192.168.1.2 / 255.255.255.0`  
   - PC2 → `192.168.1.3 / 255.255.255.0`  

3. Test connectivity using `ping`.  

4. View ARP table with:  
   ```bash
   arp -a
