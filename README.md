# Technical Portfolio
> Infrastructure Operations | Security Defense | Automation & Systems Integration

<p align="left">
  <a href="#i-infrastructure"> <img src="https://img.shields.io/badge/Section_I-Infrastructure-blue?style=for-the-badge"> </a>
  <a href="#ii-automation"> <img src="https://img.shields.io/badge/Section_II-Automation-green?style=for-the-badge"> </a>
  <a href="#iii-development"> <img src="https://img.shields.io/badge/Section_III-Development-orange?style=for-the-badge"> </a>
  <a href="#iv-database"> <img src="https://img.shields.io/badge/Section_IV-Database-red?style=for-the-badge"> </a>
</p>

---

<div id="i-infrastructure"></div>

## I. Enterprise Infrastructure & Hybrid Cloud Architecture

### Cloud Network & 10G Backbone
<img src="雲端平台虛擬網路：10G%20骨幹架構與%20ipSAN%20儲存流量隔離實務.png" width="100%">

### vSAN Cluster Configuration
<img src="vSAN%20超融合架構：實體磁碟組配置.png" width="100%">

### Enterprise Virtualization & vSAN Maintenance
<img src="企業級虛擬化架構部署與%20vSAN%20儲存集群維運實績.png" width="100%">

---

<div id="ii-automation"></div>

## II. Industrial Automation & Monitoring Systems

### Industry 5.0: Smart AGV & HMI Collaboration
<img src="工業%205.0：智慧型自動搬運監控與人機協作系統實作.png" width="100%">

### Cross-Segment Health Check (Automated)
<img src="跨網段基礎設施自動化健康檢查%20(Health%20Check).png" width="100%">

### Integrated Monitoring & Backup
<img src="整合式自動化監控與資料庫備援實務.png" width="100%">

---

<div id="iii-development"></div>

## III. Automation Development & Technical Management

### vSphere/vSAN Automation Scripting
```python
# vCenter API Integration for Automated Health Checks
import pyVim.connect
from pyVmomi import vim

def check_vsan_health(cluster_name):
    # Core Logic for Automated Log Analysis
    status = vsan.QueryHealth(cluster_name)
    return status
