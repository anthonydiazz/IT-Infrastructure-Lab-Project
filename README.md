# 🚀 IT-Infrastructure-Lab-Project



## ✅ Part 1: Server Setup & Domain Configuration

- Installed Windows Server 2022 in VirtualBox

- Configured two NICs: NAT and Internal Network

- Installed core roles: AD DS, DHCP, and Remote Access

- Created Organizational Units (IT, Finance)

- Added domain users: Helpdesk (IT), Bruce Wayne (Finance)


View Part 1: 🔗 [← Go to Part 1: Windows Server 2022 Setup](https://github.com/anthonydiazz/Server2022)


## 🖥️ Part 2: Client Setup & Domain Integration

- Created and configured two Windows 10 VMs

- Joined both clients to the domain anthonytech.com

- Installed RSAT tools on Helpdesk machine

- Applied domain-wide password and lockout policies via GPO

- Created and filtered a GPO that disables Task Manager only for Bruce Wayne


View Part 2: 🔗 [←  Part 2: Client VM Setup, Domain Join & GPO Enforcement](https://github.com/anthonydiazz/ClientVMs)



## 🛠️ Part 3: Troubleshooting & Remote Management

- Resolved a domain lockout issue for user Bruce Wayne

- Reset password and forced change at next login

- Configured remote desktop permissions for Helpdesk

- Successfully performed Remote Desktop Connection to Desktop2



View Part 3: [Part 3: Troubleshooting - Account Lockout and Remote Assistance](https://github.com/anthonydiazz/ClientTroubleshooting)
