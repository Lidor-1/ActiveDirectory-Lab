# Active Directory Home Lab

**Quick TL;DR:** Built a small Active Directory lab with **1 Windows Server 2019** and **1 Windows 10 client**, created a domain, managed users and groups, and used an **automated bulk user creation script with PowerShell**.

This lab was designed to get hands-on experience with Active Directory, including domain setup, user management, and client authentication.

## What I Did
- Installed **Windows Server 2019** and promoted it to a **Domain Controller**
- Created a domain: `mydomain.com`
- Added **Organizational Units (OUs)** and groups
- Ran a **PowerShell script** to generate ~1,000 random user accounts
- Set up a **Windows 10 VM client** and joined it to the domain
- Logged in as domain users to test authentication

> **Note:** The PowerShell script used for bulk user creation was sourced from an online tutorial and used for demonstration purposes.

## Screenshots
Included in `/screenshots/`:

- `server-ad.png` → Server setup and Domain Controller  
- `bulk-users.png` → PowerShell script generating users  
- `client-login.png` → Client machine joined to the domain and logged in  

## What I Learned
- How to set up a domain and manage users in Active Directory  
- Organizing users into OUs and groups for easier management  
- Using PowerShell to automate bulk user creation  
- How a Windows client authenticates to a domain controller
