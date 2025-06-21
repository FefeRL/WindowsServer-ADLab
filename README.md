# Windows Server 2019 - Active Directory Lab

## 🔧 Overview
Hands-on lab where I configured a Windows Server 2019 VM as a Domain Controller using Active Directory Domain Services (AD DS), DNS, and Group Policy to manage users, groups, and permissions in a simulated corporate network.

## 🛠️ Tools & Tech Used
- VMware Workstation 17 Player  
- Windows Server 2019  
- Active Directory Domain Services (AD DS)  
- DNS  
- Group Policy Management Console (GPMC)  

## 🗂️ Key Tasks Performed
- Promoted the server to a Domain Controller (`lab.local`)
- Created Organizational Units: `OU_Users`, `OU_Groups`, and `OU_Computers`
- Created 3 users (Alice, Bob, Charlie) with domain-level login
- Configured two AD groups: `IT_Team`, `HR_Team`
- Used Group Policy to allow users in those groups to log in to the server
- Tested successful logins using domain credentials

## 💻 Screenshots
_(Upload and link screenshots here — or drag them into the repo if you're using GitHub Desktop or the web file uploader)_

## ✅ Skills Demonstrated
- Active Directory Administration  
- Group Policy Configuration  
- Domain/DNS Configuration  
- User/Group Access Control  
- System Administration (Windows Server)
