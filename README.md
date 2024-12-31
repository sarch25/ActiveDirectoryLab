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

## Walk-Through
#### Downloaded VirtualBox
![Screenshot 2024-04-02 103439](https://github.com/user-attachments/assets/f0d2499b-780c-439f-a6c0-148c955f3c1f)
#

#### Configured the Domain Controller and installed the Windows Server 2019 ISO on the system to establish and manage the Domain Controller environment.
![Screenshot 2024-12-24 105326](https://github.com/user-attachments/assets/b3e70a49-5889-4d6a-a4a9-07aee9f602d4)
#

#### Installed Active Directory Domain Services and created a new domain for centralized network management.
![Screenshot 2024-12-27 184434](https://github.com/user-attachments/assets/4ffc86e1-6b2b-41ee-a288-e13eb23d3936)
![Screenshot 2024-12-27 184844](https://github.com/user-attachments/assets/32e0f446-7004-4fba-a307-815b2103a910)
![Screenshot 2024-12-27 185339](https://github.com/user-attachments/assets/700ea11c-0971-4371-8007-58d5d73e763e)
#

#### Implemented Remote Access Server (RAS) with Network Address Translation (NAT) on the Domain Controller to enable clients on the private virtual network to access the internet.
![Screenshot 2024-12-27 195136](https://github.com/user-attachments/assets/67a7471d-9c7b-4273-a097-4fa0435a3377)
![Screenshot 2024-12-27 195536](https://github.com/user-attachments/assets/b6b354f0-7223-42b0-a253-7385f35c19a4)
![Screenshot 2024-12-27 195655](https://github.com/user-attachments/assets/abfd73f9-657d-493c-8de6-b95dc72f7c1a)

#
#### Set up Network Address Translation (NAT) to enable internal clients on the private network to connect to the internet.
![Screenshot 2024-12-27 200818](https://github.com/user-attachments/assets/c16bb3e9-8ff7-4328-bcbb-3314bb071b1e)
![Screenshot 2024-12-27 201130](https://github.com/user-attachments/assets/fe197c5d-c5d8-498a-b739-e0c198749a84)
#

#### Configured a DHCP server on the Domain Controller to automatically assign IP addresses to clients on the private internal network. This setup enables clients to access the internet and browse seamlessly, replicating functionality similar to an office or school environment.
![Screenshot 2024-12-28 110648](https://github.com/user-attachments/assets/4f2ab673-a38d-4659-82bc-ce403497e528)
![Screenshot 2024-12-28 110836](https://github.com/user-attachments/assets/cbb8767f-2b38-4c28-ad6f-83011445f22e)
#

#### Defined the IP range scope for the DHCP server to allocate addresses dynamically to clients on the network.
![Screenshot 2024-12-28 112820](https://github.com/user-attachments/assets/85c5a4c1-a85e-4f53-b0c0-24cfba804dc0)
![Screenshot 2024-12-28 113538](https://github.com/user-attachments/assets/2e0a146f-dcb8-4883-b657-995a1823d3d8)
#



#### Active Directory user accounts successfully created and displayed, showcasing automation of 1,000 users using a PowerShell script.
![Screenshot 2024-04-02 115537](https://github.com/user-attachments/assets/f3c92d7e-e468-4009-8169-896eaa58219e)
#



#### Set up client systems on the Internal Network to automatically receive IP addresses from the Domain Controller's DHCP server, ensuring efficient network configuration and smooth access to resources.
![Screenshot 2024-04-02 120147](https://github.com/user-attachments/assets/73f95948-e6f6-402f-b9a6-27fa56ac8bfb)



#
#### Added myself as a new user account in Active Directory to test login and connectivity on a client computer.
![Screenshot 2024-04-02 120754](https://github.com/user-attachments/assets/1623176c-09db-4697-a834-bd1978ddeb99)

#### I was able to access the internet on the client computer using a user login through the Domain Controller's Internal Network.
![Screenshot 2024-04-02 121237](https://github.com/user-attachments/assets/f8b3aa94-f6ac-4085-9373-2d7f50e330a4)
#



#### This shows one address lease in DHCP from the Domain Controller, assigned to the Client1 computer we used to access the internet. The DHCP server successfully assigned an IP address to the client.
![Screenshot 2024-04-02 122004](https://github.com/user-attachments/assets/9dae6972-0dea-487f-97b3-e72770cbd45f)
#












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
