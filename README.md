## Lab Overview: Windows Server and Active Directory 
The lab was created to develop hands-on IT support and system administration skills, including user management, domain authentication, password resets, account lockout management, and basic access control.
### VirtualBox Overview

![VirtualBox Lab Environment](images/VirtualBox.png)

### Windows Server 2022

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

### Evidence
### Created an OU

![OUs](images/New-OU.png)

### Created a new Group

![Groups](images/Create-Group.png)

### Created a new User

![Groups](images/New-User.png)

### Added user to a Group

![Add](images/add-user-to-group.png)

## 4. Joined client to the Domain 
### Client : Jeremy Lewis
![Add](images/Jeremy-02.png)

### 4.1. Client Network Configuration

Configured the Windows client network settings to communicate with the Active Directory Domain Controller.

### Evidence
### Set the preferred DNS server to the Domain Controller's IP address

![Client DNS Configuration](images/DNS-server.png)

### Verified network connectivity to the Domain Controller

![ping DC](images/ping-DNS.png)

### 4.2. Domain Authentication
Joined the Windows client to the Active Directory domain and verified that a domain user could authenticate successfully.

### Evidence
### Joined the Windows client to the domain

![Authenticated Domain User](images/Domain-joined-confirmation.png)

### Client successfully joined to the domain

![ADD](images/Jeremy-01.png)

### Signed in using client's user account

![Domain Login](images/sign-in.png)

### Verified the authenticated user and domain

![ADD](images/whoami.png)

## 6. Password Reset
Practised resetting a user's Active Directory password, simulating a common Service Desk request.

### Evidence
### Reset the user's password & Configured the account to require a password change at next logon

![User Account](images/Patricia-reset-password.png)

### Password was successfully changed

![User Account](images/Patricia-password-changed.png)







