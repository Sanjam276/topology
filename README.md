#  Home Network Documentation

## 1.  Physical Topology
- **Device Locations:**
    - Router: Living Room
    - Switch: Connected to router
    - Access Points:  Living Room and near the router
    - Devices:
        - Desktop (Ethernet) 
        - Phone (Wi-Fi)
        - Laptop (Wi-Fi)

![sssss2](https://github.com/user-attachments/assets/efca8192-bc25-4c77-9579-5012bcd07086)


## 2.  Logical Topology
- **Network Segmentation:**
    - VLAN 10: Management (e.g., Router, Switch, Access Points)
    - VLAN 40: Home Devices (e.g., PCs, Laptops, Phone)

![ssssssss1](https://github.com/user-attachments/assets/2e0325ab-5eea-4eda-af2f-17217e77565a)


## 3.  Addressing Documentation
- **IP Schema:**
    - Router: `192.168.x.x/24` – Management
    - Switch: `192.168.x.x/24` – Management
    - AP 1: `192.168.x.x/24`
    - 
- **DHCP Ranges:**
    - `192.168.x.x - 192.168.x.x` – Main devices

- **Static IPs:** Assigned for critical devices such as  switches, and access points.

## 4.  Device Information

| Device         | Model                  | IP Address         | Location        | Notes                       |
|----------------|------------------------|--------------------|-----------------|-----------------------------|
| Router         | Shaw Arris XB7         | 192.168.x.x        | Living Room     | Primary router with Wi-Fi 6 |
| Switch         | Cisco SG350            | 192.168.x.x        | Office          | Managed switch              |
| AP 1           | Shaw BlueCurve Pod     | 192.168.x.x        | Bedroom 1       | Wi-Fi 6 Pod                 |
| Laptop         | ASUS                   | 192.168.x.x        | Living Room     | Main Devices                |
| Phone          |Apple                   | 192.168.x.x        | Front Door      | Main Devices                |
| Desktop        | HP                     | 192.168.x.x        | Backyard        | Main Devices                |
  

## 5. Configuration Management
- **Backup Policy:**  
    - Backup configurations regularly for router, switches, and APs.
    - Store encrypted copies in multiple locations (e.g., cloud, external drive).

- **Change Management:**  
    - Document any network changes (e.g., new devices, configuration updates).
    - Maintain a version-controlled config history.


## 6.  Secure Storage of Login Credentials
- **Method Used:**  
    - **Password Manager:** Store all credentials securely using a password manager **1Password**.
    - **Multi-Factor Authentication (MFA):** Enable MFA for router and cloud services.

