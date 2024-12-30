<h1>Active Directory with PowerShell</h1>

## Summary

Created a home lab environment using Oracle VirtualBox with two virtual machines: Windows Server 2019 and Windows 10. Configured Windows Server 2019 as a Domain Controller, setting up Active Directory for centralized resource and user management. 

Implemented network services, including NAT, routing, and DHCP, to enable seamless IP assignment and connectivity within the private network. 

Automated user management by creating 1,000 Active Directory users via a PowerShell script. Successfully integrated the Windows 10 client into the domain, completing the Active Directory infrastructure setup.

This project demonstrates foundational IT and cybersecurity skills, emphasizing proficiency in deploying and managing corporate level infrastructure. It highlights skills in user and resource management, secure network configuration, and automation—critical competencies for ensuring efficient and secure IT operations in real-world environments.

![Screenshot 2024-04-02 122004](https://github.com/user-attachments/assets/fdf1cf65-6f52-4a30-aff3-f65222139f35)

### Skills Learned


- Setting up a Domain Controller and Active Directory infrastructure within a virtualized environment using Oracle VirtualBox
- Configuring network components such as NAT, Routing, and DHCP for seamless connectivity and IP address management
- Leveraging PowerShell scripting for automating user creation processes, improving efficiency in user management tasks
- Integrating client VMs into the Active Directory domain, enabling centralized user authentication and resource management
- Recognizing the significance of Active Directory in network administration and user management, with implications for real-world corporate network setups.

### Tools Used


- Oracle VirtualBox for virtual machine deployment
- Windows Server 2019 for the Domain Controller VM
- Windows 10 for the client VM
- PowerShell scripting for user creation automation
- NAT, Routing, and DHCP for networking configurations

## Images
![Screenshot 2024-04-02 103439](https://github.com/user-attachments/assets/f0d2499b-780c-439f-a6c0-148c955f3c1f)
#

Configured the Domain Controller and installed the Windows Server 2019 ISO on the system to establish and manage the Domain Controller environment.
![Screenshot 2024-12-24 105326](https://github.com/user-attachments/assets/b3e70a49-5889-4d6a-a4a9-07aee9f602d4)
#

Installed Active Directory Domain Services and created a new domain for centralized network management.
![Screenshot 2024-12-27 184434](https://github.com/user-attachments/assets/4ffc86e1-6b2b-41ee-a288-e13eb23d3936)
![Screenshot 2024-12-27 184844](https://github.com/user-attachments/assets/32e0f446-7004-4fba-a307-815b2103a910)
![Screenshot 2024-12-27 185339](https://github.com/user-attachments/assets/700ea11c-0971-4371-8007-58d5d73e763e)
#

Installed Remote Access Server (RAS) with Network Address Translation (NAT) on the Domain Controller to enable clients on the private virtual network to access the internet. This configuration ensures seamless connectivity while maintaining centralized management through the Domain Controller.
![Screenshot 2024-12-27 195136](https://github.com/user-attachments/assets/67a7471d-9c7b-4273-a097-4fa0435a3377)
![Screenshot 2024-12-27 195345](https://github.com/user-attachments/assets/c74d09cf-a182-4146-ac7a-f2cf617a3dbe)
![Screenshot 2024-12-27 195536](https://github.com/user-attachments/assets/b6b354f0-7223-42b0-a253-7385f35c19a4)
![Screenshot 2024-12-27 195655](https://github.com/user-attachments/assets/abfd73f9-657d-493c-8de6-b95dc72f7c1a)

#
Configured Network Address Translation (NAT) to enable internal clients on the private network to connect to the internet.
![Screenshot 2024-12-27 200818](https://github.com/user-attachments/assets/c16bb3e9-8ff7-4328-bcbb-3314bb071b1e)
![Screenshot 2024-12-27 201130](https://github.com/user-attachments/assets/fe197c5d-c5d8-498a-b739-e0c198749a84)
![Screenshot 2024-12-27 201429](https://github.com/user-attachments/assets/f579a669-e19d-4158-9511-730fe5238f0d)
#

Configured a DHCP server on the Domain Controller to automatically assign IP addresses to clients on the private internal network. This setup enables clients to access the internet and browse seamlessly, replicating functionality similar to an office or school environment.









Active Directory user accounts successfully created and displayed, showcasing automation of 1,000 users using a PowerShell script.
![Screenshot 2024-04-17 105846](https://github.com/sarch25/ActiveDirectoryLab/assets/130470960/6fc39772-4865-483e-be2f-224b377c0c96)
![Screenshot 2024-04-02 115304](https://github.com/sarch25/ActiveDirectoryLab/assets/130470960/5dd3703d-43e7-4939-a751-d399e3b2726f)
#
![Screenshot 2024-04-02 122004](https://github.com/sarch25/ActiveDirectoryLab/assets/130470960/5dc9d953-bec5-4951-a604-33bb314d1514)
![Screenshot 2024-04-02 112718](https://github.com/sarch25/ActiveDirectoryLab/assets/130470960/515974ea-f491-408f-8e7d-193a888382b7)
![Screenshot 2024-04-02 111730](https://github.com/sarch25/ActiveDirectoryLab/assets/130470960/1b937a0a-9151-4f23-a4ab-768248ff7b28)

Network services, including NAT and DHCP, implemented to enable connectivity and IP assignment within the private lab environment.
![Screenshot 2024-04-02 111635](https://github.com/sarch25/ActiveDirectoryLab/assets/130470960/23eb8fd3-e3e7-4687-943f-f4e29d641da0)




Every screenshot should have some text explaining what the screenshot is about.


<h2>Description</h2>
In this lab we're going.......
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Users in Powershell: <br/>
<img src="https://i.imgur.com/42t2x9V.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
