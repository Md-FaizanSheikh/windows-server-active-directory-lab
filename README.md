# Windows Server & Active Directory Administration Lab

A hands-on Windows Server 2022 and Active Directory administration lab built using Oracle VirtualBox.

## Project Overview

This project demonstrates the deployment and administration of a Windows Server 2022 Active Directory environment with a Windows 11 domain client.

The lab focuses on centralized identity management, DNS, DHCP, Group Policy, domain authentication, and basic endpoint administration.

## Environment

- Windows Server 2022 Standard Evaluation
- Windows 11 Pro
- Oracle VirtualBox
- Active Directory Domain Services
- DNS Server
- DHCP Server
- Group Policy Management

## Domain Configuration

- Domain: `corp.local`
- Domain Controller: `DC01`
- Client: `CLIENT01`
- Domain Controller IP: `192.168.50.10`
- Lab Network: `192.168.50.0/24`

## Key Implementations

- Created Active Directory domain `corp.local`
- Configured Organizational Units for IT, HR, Finance, and Management
- Created and managed domain user accounts
- Configured DNS for the Active Directory domain
- Configured and activated a DHCP scope
- Joined Windows 11 client to the domain
- Configured domain password policy
- Configured account lockout policy
- Created Group Policy for IT desktop restrictions
- Configured centralized desktop wallpaper
- Restricted Control Panel and Windows Settings access
- Validated domain authentication and Group Policy application
- Verified DNS and DHCP functionality from the domain client

## Validation

The environment was validated by:

- Successful domain-user authentication
- Successful domain membership of CLIENT01
- DHCP address assignment
- DNS name resolution
- Group Policy application
- Password and account lockout policy verification

## Project Evidence

Screenshots and supporting documentation are organized in the repository to demonstrate the configuration and validation of the lab environment.

## Skills Demonstrated

- Windows Server Administration
- Active Directory
- User and Organizational Unit Management
- DNS
- DHCP
- Group Policy
- Windows Client Domain Management
- Basic Network Configuration
- Troubleshooting and Validation
