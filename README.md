# ngthsang-Network-Project---Enterprise
# Palo Alto User-ID (Agentless via WinRM)

## 🎯 Objective
Integrate Palo Alto firewall with Active Directory
using agentless User-ID via WinRM.

## 🧪 Lab Environment
- Firewall: PA-VM (PAN-OS 11.x)
- Windows Server 2022 (AD)
- Emulator: PNETLab

## 🗺️ Topology
![Topology](topology.png)

## 🔧 Configuration Scope
- Windows WinRM
- Palo Alto User-ID settings
- Service Account permissions

## ⚠️ Issues & Troubleshooting
- DCOM authentication error
- Access denied during user mapping

## ✅ Result
- User-IP mapping successful
- Policy based on AD groups working
