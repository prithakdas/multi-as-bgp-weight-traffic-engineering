# Multi-AS BGP Weight Traffic Engineering Lab

## 📌 Project Overview

This project demonstrates a Multi-Autonomous System (Multi-AS) BGP topology implemented in GNS3. The primary objective of this lab is to perform traffic engineering using the BGP Weight attribute to control outbound path selection.

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

- Platform: GNS3  
- Routing Protocol: Border Gateway Protocol (BGP)  
- Topology Type: Multi-AS Environment  
- Traffic Engineering Method: Weight attribute manipulation  

---

## 🌐 Network Topology

The topology consists of multiple routers placed in different Autonomous Systems. eBGP sessions were established across AS boundaries to enable route exchange.

Refer to `topology.png` for the complete network diagram.

---

## ⚙️ Implementation Details

### 1️⃣ BGP Neighbor Configuration

eBGP peering was established between routers belonging to different Autonomous Systems.

Verification command:
```
show ip bgp summary
```

---

### 2️⃣ Route Advertisement

Internal networks were advertised into BGP using network statements and validated for proper propagation across AS boundaries.

Verification command:
```
show ip bgp
```

---

### 3️⃣ Traffic Engineering Using Weight Attribute

The BGP Weight attribute was configured to influence outbound path selection.

- Higher weight value was assigned to the preferred path  
- BGP selected the path with the highest weight  
- Path selection behavior was validated using BGP verification commands  

---

## 🔍 Verification Commands Used

```
show ip bgp
show ip bgp summary
show ip route
```

---

## 🎯 Project Outcome

- Successfully established eBGP sessions across multiple Autonomous Systems  
- Implemented traffic engineering using the Weight attribute  
- Controlled outbound routing decisions as expected  
- Verified correct BGP best path selection behavior  

---

## 📁 Repository Structure

```
multi-as-bgp-weight-traffic-engineering
  ├── MultiAS_BGP_Lab_GNS3/
      ├── MultiAS_BGP_Weight_Traffic_Engineering.gns3
      └── project-files/
  ├── topology.png
  ├── BGP_MultiAS_Routing_Traffic_Engineering.pdf
  └── README.md
```

---

## 🚀 Key Learning Outcomes

- Understanding of Inter-AS routing behavior  
- Practical implementation of BGP attributes  
- Traffic engineering using Weight  
- Real-world troubleshooting of BGP sessions  
- Deeper insight into BGP best path decision process  

---

## 👨‍💻 Author

Prithak Das  
Master's in Advanced Networking & Cybersecurity
