## Lab Overview: Windows Server and Active Directory 
The lab was created to develop hands-on IT support and system administration skills, including user management, domain authentication, password resets, account lockout management, and basic access control.
### VirtualBox Overview

![VirtualBox Lab Environment](images/VirtualBox.png)

### WIndows Server 2022

![Windows Server](images/Server-01.png)

### 1. Static IP Configuration
Configured a static IPv4 address on the Windows Server to provide a consistent network address for the Domain Controller and Active Directory services.

**Configuration included:**
- Static IPv4 address
- Subnet mask
- Default gateway
- Preferred DNS server

![static ip address](images/static-ip-address.png)

### 2. Domain Controller 
Promoted Windows Server as a Domain Controller by installing Active Directory Domain Services (AD DS) and creating a Windows domain.

**Tasks performed:**
- Installed the Active Directory Domain Services role
- Promoted the server to a Domain Controller
- Created and configured the lab domain

![DC](images/domain-controller.png)

### 3. User & Group Management
Created test user accounts and security groups in Active Directory to practise common user administration tasks.

**Tasks performed:**
- Created user accounts
- Created organisational units
- Added users to appropriate groups

### Evidence
### Created an OU

![OUs](images/New-OU.png)

### Created a new Group

![Groups](images/Create-Group.png)

### Created a new User

![Groups](images/New-User.png)

### Added user to a Group

![Add](images/add-user-to-group.png)

### 4. Domain Authentication

Joined the Windows client to the Active Directory domain and verified that a domain user could authenticate successfully.

**Tasks performed:**
- Joined the Windows client to the domain
- Signed in using a domain user account
- Verified the authenticated user and domain

### Evidence

![Domain Login](screenshots/domain-login.png)

![Authenticated Domain User](screenshots/whoami.png)



