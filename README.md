# Multi-AS BGP Weight Traffic Engineering Lab

## 📌 Project Overview

This project demonstrates a **Multi-Autonomous System (Multi-AS) BGP topology** implemented in GNS3.  
The primary objective of this lab is to perform **traffic engineering using the BGP Weight attribute** to control outbound path selection.

The lab simulates an enterprise-style inter-AS routing environment where BGP is used to exchange routes between different Autonomous Systems and manipulate routing decisions.

---

## 🧠 Concepts Covered

- eBGP configuration between multiple Autonomous Systems  
- BGP route advertisement and propagation  
- BGP Weight attribute configuration  
- BGP Best Path Selection process  
- Traffic engineering fundamentals  
- BGP verification and troubleshooting  

---

## 🏗️ Lab Environment

- **Platform:** GNS3  
- **Routing Protocol:** Border Gateway Protocol (BGP)  
- **Topology Type:** Multi-AS Environment  
- **Traffic Engineering Method:** Weight attribute manipulation  

---

## 🌐 Network Topology

The topology consists of multiple routers placed in different Autonomous Systems.  
eBGP sessions are established across AS boundaries to enable route exchange.

Refer to `topology.png` for the complete network diagram.

---

## ⚙️ Implementation Details

### 🔹 1. BGP Neighbor Configuration

eBGP peering was established between routers belonging to different Autonomous Systems.

Verification:
