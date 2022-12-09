## zwifft-offline
How to play offline [zwift.com](zwift.com) using [https://github.com/zoffline/zwift-offline](https://github.com/zoffline/zwift-offline)  
### Requirements:
* ProxMox  
* terraform (proxmox provider)  
### How to install ProxMox  
1. Install as base OS (Using the Proxmox VE Installer section)  
[https://pve.proxmox.com/pve-docs/chapter-pve-installation.html](https://pve.proxmox.com/pve-docs/chapter-pve-installation.html)  
2. Create users in PM  
[https://registry.terraform.io/providers/Telmate/proxmox/latest/docs#creating-the-proxmox-user-and-role-for-terraform](https://registry.terraform.io/providers/Telmate/proxmox/latest/docs#creating-the-proxmox-user-and-role-for-terraform)  
3. Use connection.tf for deploy infrastructure  
