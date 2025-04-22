# **Blocklist Setup for Xbox & PlayStation Servers**

This repository provides various blocklists designed to block telemetry, ads, firmware updates, licensing checks, and other unwanted server connections for Xbox and PlayStation. These blocklists help improve privacy, reduce network clutter, and prevent unwanted updates.

### **Blocklist Descriptions:**

#### **1. Xbox Blocklists:**
These blocklists target Xbox-related servers, including those for ads, telemetry, and firmware updates.

- **microsoft-ad-servers.txt**: Block Xbox ad servers to stop advertisement traffic and tracking.
- **microsoft-telemetry-servers.txt**: Block telemetry servers used by Xbox to send data back to Microsoft for analytics and diagnostics.
- **more-xbox-servers.txt**: Additional Xbox-related servers that may not be covered by the above lists.
- **reallybad-xboxlive-servers.txt**: Block Xbox firmware updates and licensing servers to prevent automatic console updates and licensing checks.

#### **2. PlayStation Blocklists:**
These blocklists target PlayStation-related servers, including telemetry and other unwanted connections.

- **playstation-telemetry-servers.txt**: Block PlayStation telemetry servers that send usage data and diagnostic information to Sony.
- **sony-servers.txt**: Contains general PlayStation servers, such as those for authentication and service access. It's recommended to only block region-specific servers to avoid interfering with necessary services (e.g., store access, game downloads).

---

### **Usage Information:**

1. **Xbox-related Blocklists**: These lists aim to block unwanted Xbox server connections, including those used for telemetry, ads, and system updates.
   
2. **PlayStation-related Blocklists**: These lists aim to block unwanted telemetry, ads, and unnecessary PlayStation servers, improving your privacy and preventing unwanted data sharing.

---

### **Pi-hole Recommended for Global Blocking:**
- If your router doesn't support global blocking (blocking across all devices in your network), it's recommended to use **Pi-hole**. Pi-hole acts as a local DNS sinkhole that can block unwanted domains at the network level, effectively preventing your devices from reaching blocked servers, including Xbox and PlayStation servers listed here.
  
- Pi-hole allows you to add these lists to block unwanted connections on all devices connected to your network, even if your router doesn’t have the capability to globally block domains.
