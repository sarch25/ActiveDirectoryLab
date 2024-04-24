<h1>Active Directory Lab with PowerShell</h1>

## Summary

Active Directory (AD) is one of the most important network management tools that businesses use all over the world. It functions as a centralized database that contains information on computers, users, and groups on a network. Its main purpose is to create a centralized hub for managing users, permissions, and security settings, hence streamlining tasks like user authentication, access control, and policy enforcement. By efficiently optimizing resource management, AD improves security, productivity, and network operations and enables enterprises to maintain control and supervision throughout their IT environments.

I used Oracle VirtualBox to install two virtual machines, one running Windows 10 and the other Windows Server 2019, which I used to set up my home lab environment for Active Directory (AD). Installing Windows Server 2019 and configuring Active Directory as well as creating a domain for centralized resource and user management were all necessary steps in configuring the Domain Controller. Network setups such as NAT, Routing, and DHCP setup made sure that devices on the private network could connect and assign IP addresses without any problems. Automation was crucial since it streamlined user administration procedures by enabling the creation of 1,000 users in Active Directory with the help of a PowerShell script. Creating the client VM running Windows 10 and integrating it into the AD domain concluded the setup, demonstrating successful implementation and integration of AD infrastructure within the VirtualBox environment.

![Screenshot 2024-04-02 115304](https://github.com/sarch25/ActiveDirectoryLab/assets/130470960/5dd3703d-43e7-4939-a751-d399e3b2726f)

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
- Network Address Translation (NAT), Routing, and DHCP for networking configurations

## Images


![Screenshot 2024-04-17 105846](https://github.com/sarch25/ActiveDirectoryLab/assets/130470960/6fc39772-4865-483e-be2f-224b377c0c96)

![Screenshot 2024-04-02 122004](https://github.com/sarch25/ActiveDirectoryLab/assets/130470960/5dc9d953-bec5-4951-a604-33bb314d1514)

![Screenshot 2024-04-02 115304](https://github.com/sarch25/ActiveDirectoryLab/assets/130470960/5dd3703d-43e7-4939-a751-d399e3b2726f)
![Screenshot 2024-04-02 112718](https://github.com/sarch25/ActiveDirectoryLab/assets/130470960/515974ea-f491-408f-8e7d-193a888382b7)
![Screenshot 2024-04-02 111730](https://github.com/sarch25/ActiveDirectoryLab/assets/130470960/1b937a0a-9151-4f23-a4ab-768248ff7b28)
![Screenshot 2024-04-02 111635](https://github.com/sarch25/ActiveDirectoryLab/assets/130470960/23eb8fd3-e3e7-4687-943f-f4e29d641da0)




Every screenshot should have some text explaining what the screenshot is about.

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

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
