# Small-Business-Network-Project
SMB Project
I worked with a small team to build out and configure a small business network using GNS and FortiClient VPN.

**Starting topology**

![image](https://github.com/DangerDan87/Small-Business-Network-Project/assets/134319969/89eeaa14-5c31-419a-8227-39822c203f32)

**Final network topology**

![image](https://github.com/DangerDan87/Small-Business-Network-Project/assets/134319969/d32748dc-8f2a-4151-a34f-5b2bcbc616d8)

Set up a SMB (small/medium business) network, with a LAN, DMZ, and Guest network. Utilized a FortiNet firewall and configured both static and dynamic IP address for systems.
Configured the interfaces in CLI and we configured the LAN interface and verified it was correct. We also created a Windows domain environment, an IIS server, a Windows FTP server, a Win10 workstation, a LAMP webserver running UNBUNTU, hosting a wiki, a Fortigate firewall, with a VIP for a DMZ webserver

![image](https://github.com/DangerDan87/Small-Business-Network-Project/assets/134319969/73761beb-a476-445c-a563-f362842cfe96)
![image](https://github.com/DangerDan87/Small-Business-Network-Project/assets/134319969/fda390b6-f409-49de-b894-0b32bb6963f7)

setting up the DHCP

![image](https://github.com/DangerDan87/Small-Business-Network-Project/assets/134319969/ae21cfe1-08c7-475a-b05f-a5e0c08b5453)

Once the LAN and DHCP and DNS servers were set up we also added a WIN 2012 server to fill the Active Directory Domain Services role and installed Active Directory. Once the directory was created we added users and admin and group policies.
![image](https://github.com/DangerDan87/Small-Business-Network-Project/assets/134319969/aef56605-2183-4be0-9150-2b1507028255)
![image](https://github.com/DangerDan87/Small-Business-Network-Project/assets/134319969/989fdc9c-bb4a-4618-b9f6-e7b4e1cfb669)

Once the active directory and users were set up we added another server for Internet Information Services "IIS" 
![image](https://github.com/DangerDan87/Small-Business-Network-Project/assets/134319969/91238b90-9ae4-4bb2-8fa9-2860bc106d40)

Created a LAMP (Linux, Apache, MySQL, PHP/Perl/Python) webserver on the DMZ network

![image](https://github.com/DangerDan87/Small-Business-Network-Project/assets/134319969/72e03313-75a3-4cf2-be42-e4bee6806cfc)
![image](https://github.com/DangerDan87/Small-Business-Network-Project/assets/134319969/3ec790a0-2b6d-4c77-b03f-51ce1d3b9615)

We also configured a DokuWiki to document our work and process. This allowed us to provide information on how configurations were created and even potential issues "Vulnerabilities" and fixes "Hardening" for the network.

![image](https://github.com/DangerDan87/Small-Business-Network-Project/assets/134319969/421c8301-bd24-46a6-9505-9ebb51f124bb)

Created a FTP server on the DMZ network. This allows up to access files from the server from outside of the network. Below is also a screenshot showing access from an internet browser.
![image](https://github.com/DangerDan87/Small-Business-Network-Project/assets/134319969/e9559f5b-abc4-4431-a713-066d6d900b41)
![image](https://github.com/DangerDan87/Small-Business-Network-Project/assets/134319969/7720b657-4beb-4c3c-9425-913c2eadc440)


To end the project we also ran scans through Greenbone to identify the weakness and provide additional information for vulnerabilieties and hardening information for the network.

![image](https://github.com/DangerDan87/Small-Business-Network-Project/assets/134319969/3d65c65b-31e2-4b04-ade9-6ad290a80f9e)

