# Huawei Router IPTV Configuration

This repository contains the **cleaned and structured configuration** for the Huawei router **`rtr-iptv-01`**, running version **V200R021C00SPC100**.  
It is designed for **IPTV, Internet, and NPIX peering** with secure authentication, routing policies, and monitoring enabled.

---

## 📌 Features

- **System & Time**
  - Hostname, timezone, and NTP synchronization

- **AAA & Security**
  - TACACS+ authentication, authorization, and accounting
  - Fallback to local admin account
  - SSH, STelnet, and SFTP access enabled

- **SNMP Monitoring**
  - SNMP communities for external monitoring

- **VLAN & Interfaces**
  - VLAN-based service separation (Management, Internet, IPTV)
  - Trunk uplinks and routed VLAN interfaces

- **Routing**
  - OSPF for internal routing
  - BGP for external peering
  - IP Prefix Lists for route filtering:
    

- **Access Control**
  - ACL to restrict traffic and enforce security policies

---

## 🖥️ Supported Router Models

This configuration template is verified to work on the following Huawei router families:

- **Huawei Netengine 8000M Series** (Carrier-grade core/edge routers)
-
- **Huawei Netengine 8000F Series** (Broadband multi-service edge routers, widely used for IPTV/Internet services)

⚠️ Note: Minor syntax differences may exist depending on software release and router series. Always test in a **lab environment** before production deployment.

---

## 📂 Repository Structure

