# windows-server-2019-hands-on-labs
Comprehensive hands-on labs and technical documentation covering Windows Server 2019 administration, Active Directory domain promotion, WDS, Failover Clustering, Hyper-V replication, GPO hardening, and performance monitoring.
# Windows Server 2019 Administration & Cloud Infrastructure Labs

Welcome to my **Windows Server 2019 Administration & Infrastructure** lab repository! This repository documents a comprehensive series of hands-on labs focused on deploying, configuring, securing, and managing enterprise-grade Windows Server environments, Active Directory domains, virtualization hosts, and high-availability clusters.

---

## 🛠️ Lab Environment Overview
* **Primary Hypervisor:** VMware Workstation Pro / Hyper-V
* **Operating System:** Windows Server 2019 Standard (Evaluation / Desktop Experience & Server Core)
* **Domain Name:** `ruhina.local` / `Contoso.com`
* **Management Tools:** Windows Admin Center, PowerShell, Server Manager, Failover Cluster Manager

---

## 📚 Lab Index & Table of Contents

| Lab ID | Exercise Title | Core Focus Areas |
| :--- | :--- | :--- |
| **Lab 01** | [Windows Server 2019 Setup](./EXERCISE-01-Windows-Server-Setup.md) | ISO deployment, Rufus bootable media, VMware VM provisioning, Windows Admin Center setup. |
| **Lab 02** | [WDS Implementation](./EXERCISE-02-WDS-Deployment.md) | Windows Deployment Services role, PXE boot configuration, staging `install.wim` and `boot.wim`. |
| **Lab 03** | [Post-Installation Configuration](./EXERCISE-03-Server-Post-Installation.md) | Hostname standardization (`SVR-DC01`), static IPv4 & loopback DNS, IE ESC, time synchronization. |
| **Lab 04** | [AD DS & Domain Promotion](./EXERCISE-04-ADDS-DC-Promotion.md) | Active Directory installation, promoting `SVR-DC01` to primary DC, DSRM password configuration. |
| **Lab 05** | [Data Deduplication](./EXERCISE-05-Data-Deduplication.md) | Installing and configuring Data Deduplication under File and Storage Services for space optimization. |
| **Lab 06** | [Hyper-V & Nested Virtualization](./EXERCISE-06-Hyper-V-Nested-Virtualization.md) | Enabling Hyper-V role, hardware virtualization passthrough (`VT-x/AMD-V`), Virtual Switches. |
| **Lab 07** | [Failover Clustering](./EXERCISE-07-Failover-Clustering.md) | Sysprep generalization, iSCSI storage configuration, cluster validation (`Test-Cluster`), `WFC2019`. |
| **Lab 08** | [Hyper-V Replica & DR](./EXERCISE-08-Hyper-V-Replica-DR.md) | Remote PowerShell management, Kerberos authentication, clock skew resolution (`w32tm`), VM replication. |
| **Lab 09** | [GPO Security & Hardening](./EXERCISE-09-GPO-Security-Options.md) | Account renaming policies, Microsoft Account login blocks, Control Panel & removable storage restrictions. |
| **Lab 10** | [Performance Monitoring](./EXERCISE-10-Performance-Monitoring.md) | Windows services audit, custom Data Collector Sets (`perfmon`), performance counter alert thresholds. |

---

## 🚀 How to Use This Repository
1. Click into any individual lab file (`EXERCISE-XX-*.md`) to view the step-by-step technical documentation, execution workflows, and verification checkpoints.
2. Code snippets and PowerShell commands can be copied directly for testing in your own lab environments.

---

## 👤 Author
**Ruhina Sardar Rumi**  
*Advanced Diploma in Cloud Computing Technologies | System Administration & IT Infrastructure*