# Windows Server & Active Directory Administration Lab
## Project Overview
This project involved building and managing a Windows Server environment to develop hands-on experience with server administration, Active Directory, user management, DNS, remote access, and domain authentication. 
The project focused on creating a functional Windows-based domain environment and then configuring and testing different administrative components within that environment. The screenshots throughout this documentation provide evidence of the configuration and testing performed.
### Technologies Used
- Windows Server
- Active Directory Domain Services (AD DS)
- Active Directory Users and Computers (ADUC)
- DNS
- Server Manager
- Remote Desktop Protocol (RDP)
- Windows Command Prompt
- TCP/IP networking
## 1. Windows Server Environment
The project began with the configuration of a Windows Server environment. Server Manager was used as the primary administration interface for managing the server and its installed roles.

The server environment included:

- Active Directory Domain Services
- DNS
- File and Storage Services
- Local Server management
 
The Server Manager dashboard provided a centralized view of the server’s roles and services and was used to monitor the overall environment.
server-manager.png

### Skills Demonstrated:

* Windows Server administration
* Server role management
* Server Manager
* Infrastructure configuration
* Microsoft server technologies

## 2. Active Directory Structure 
After establishing the server environment, I configured Active Directory to organize and manage users within the domain.

Using Active Directory Users and Computers, I created organizational units to provide structure within the domain.

The environment included organizational units such as:

* Naruto
    * Hidden Leaf
    * Hidden Mist

User accounts were then created and organized within the appropriate organizational units.

This portion of the project demonstrated how Active Directory can be used to create a centralized structure for managing users and resources within a Windows domain.

Skills Demonstrated:

* Active Directory
* Organizational Unit creation
* User management
* Domain organization
* Active Directory Users and Computers

## 3. User Account Configuration

After creating the user accounts, I configured and reviewed individual account properties through Active Directory.

For example, the Shikamaru N account was configured with a domain logon name and specific account settings.

The account properties provided access to settings involving:

* User logon name
* Pre-Windows 2000 logon name
* Password requirements
* Account expiration
* Account status
* Logon restrictions
* Other account options

This portion of the project provided hands-on experience with managing individual domain accounts and understanding how administrators control user access.

Skills Demonstrated:

* User account administration
* Account security
* Password configuration
* Domain account management
* Active Directory administration

## 4. Remote Desktop Connection

Once the server and user accounts were configured, I tested remote access using Remote Desktop Connection.

The remote computer was configured using the server’s IP address:

172.16.0.5

The connection was established using the domain account:

SERVER\shikamaru

This allowed me to remotely access and administer the Windows environment using the configured user account.

Skills Demonstrated:

* Remote Desktop Protocol
* Remote server administration
* IP addressing
* Domain authentication
* Windows networking

## 5. Authentication Verification

The final portion of the project involved verifying that the correct user account was authenticated after establishing the remote connection.

I opened Command Prompt and used the whoami command to identify the account currently being used.

The system returned:
server\shikamaru

This confirmed that the remote session was successfully operating under the intended domain account.

This verification step demonstrated a basic but important troubleshooting technique that can be used by system administrators to confirm user identity and investigate authentication or permission issues.

Skills Demonstrated:

* Command-line administration
* Authentication verification
* User identity troubleshooting
* Domain administration
* Windows system administration

## Project Outcome

This project provided hands-on experience building and administering a Windows Server environment from initial server configuration through user authentication and remote administration.

By completing the project, I gained practical experience with Windows Server, Active Directory, DNS, organizational units, user account management, Remote Desktop, and command-line troubleshooting.

The project also demonstrated how these technologies work together within a domain environment. Rather than configuring each technology independently, I was able to build a connected environment where users could be created in Active Directory, authenticated through the domain, and used to access the server remotely.

## Skills & Technologies
### Systems Administration
* Windows Server
* Server Manager
* Active Directory
* User administration
* Organizational Units
* Domain administration
### Networking
* TCP/IP
* IP addressing
* DNS
* Remote Desktop
* Domain authentication
### Troubleshooting & Administration
* Command Prompt
* whoami
* Account verification
* Remote access testing
* User account troubleshooting
