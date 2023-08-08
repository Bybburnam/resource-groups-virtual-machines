<h1>Let's Create Resource Groups and Deploy a Virtual Machine</h1>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop

<h2>Operating Systems Used </h2>

-Windows Server 2022
- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Azure Virtual Machine
- Internet Information Services (IIS)
- PHP Manager
- Rewrite Module
- VC Redist
- MySQL
- Heidi SQL
- osTicket v1.15.8
Link to downloads: https://drive.google.com/drive/u/0/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6

<h2>Installation Steps</h2>

<p>
Before we delve into the osTicket tutorial, it's essential to set up the foundation. We'll begin by creating a virtual machine using Microsoft Azure. This step is crucial as it forms the platform on which we'll build the osTicket system. By establishing a solid groundwork through the virtual machine setup, we'll be ready to seamlessly proceed with the osTicket installation and configuration process. Let's get started by crafting the ideal environment for a smooth osTicket experience.
</p>
<br />


<h2>Part 1 (Create a Resource Group in Azure)</h2>

<h2>Step 1:** Create a Resource Group to organize your virtual machine and its resources.</h2>
 ![image](https://github.com/Bybburnam/ostickets-prereqs/assets/102566114/693d54a2-01e7-4354-a447-e9b06e38092c) <br />
<br />
![image](https://github.com/Bybburnam/ostickets-prereqs/assets/102566114/e290ebd8-80be-423e-bd12-94d7c2c8fe27) <br />
<br />
![image](https://github.com/Bybburnam/ostickets-prereqs/assets/102566114/30150b47-027f-421c-b09a-a8bad532a8ca) <br />

<br />
<br />
<br />
<br />
<br />
<br />
<h2>Creating Virtual Machine</h2>
**We will set up a Windows 10 Virtual Machine (VM) with 2-4 Virtual CPUs, optimizing performance. Note that fewer CPUs may affect connection speed. During VM setup, ensure it creates a new Virtual Network (Vnet) for smooth connectivity**

Note: This guide assists you through the lab, with no need for strict memorization.

<h2>Step 1</h2>: Forge an Azure Virtual Machine, opting for Windows 10 and embracing 4 vCPUs for optimal performance.

![image](https://github.com/Bybburnam/ostickets-prereqs/assets/102566114/8fb96362-cafe-441d-9519-07f650146c47)  <br />


![image](https://github.com/Bybburnam/ostickets-prereqs/assets/102566114/9160735d-37dd-4a79-a3ea-08af3ec00110) <br />

![image](https://github.com/Bybburnam/ostickets-prereqs/assets/102566114/976f60b0-fa6a-40e0-9059-a3d77eec7b66) <br />

<h2>Step 2</h2>: Designate a username (e.g., labuser) and establish a robust password (e.g., osTicketPassword1!) for your VM.

By favoring 4 vCPUs in Step 2, you strike a balance between performance and connection speed, enhancing your overall experience throughout the tutorial.</p>
<br />

**COPY THE FOLLOWING SETTINGS AND INPUT TEXT FROM PICTURES BELOW. Please use login details above for later.
![image](https://github.com/Bybburnam/ostickets-prereqs/assets/102566114/895f5d91-d9f5-41b5-b232-d682b2451c28) ![image](https://github.com/Bybburnam/ostickets-prereqs/assets/102566114/aed77136-6ee1-4a6f-886a-2704b0c6f461)


<h2>CLICK NEXT UNTIL NETWORKING, ALLOW IT TO AUTOMATICALLY CREATE A NETWORK FOR THE VIRTUAL MACHINE</h2>
![image](https://github.com/Bybburnam/ostickets-prereqs/assets/102566114/3bfd89d3-38ca-4404-aaa4-63d42c3f6658)
<br />
<br />

<h2>CLICK REVIEW + CREATE, AND THEN CREATE</h2>
![image](https://github.com/Bybburnam/ostickets-prereqs/assets/102566114/4931b4ac-6244-4901-837b-765004d280b5)<br />
<br />
<br />

<h2>YOU SHOULD SEE THIS CONFIRMATION PAGE</h2>

![image](https://github.com/Bybburnam/ostickets-prereqs/assets/102566114/7b908088-9212-4a8f-ac10-733f7326266b)

<br />
<br />

<h21>Log Into Your VMs Using Remote Desktop</h2>
<h3>Log into the Remote Desktop Connection</h3>

<h2>1. Click the Microsoft Azure button on the right
2. Click vm-osticket Virtual Machine
3. Copy Public IP ADDRESS</h2>

<br />
<br />
![image](https://github.com/Bybburnam/resource-groups-virtual-machines/assets/102566114/8d4a59d2-60a6-4d0d-a587-21a5e1c57837)

<h2>Click the start menu on your computer, type in Remote Desktop Computer and paste public IP addres, and then click connect</h2>

![image](https://github.com/Bybburnam/resource-groups-virtual-machines/assets/102566114/562477fb-a047-4e45-8b92-182476c8f1fa)
<br />
<br />
<h2>This pop up box should come up, click more options if your name appears, input log-in details from above</h2>
![image](https://github.com/Bybburnam/resource-groups-virtual-machines/assets/102566114/ef82fbfe-8f02-4ed7-a22a-9278af1d7c56)
<br />
<br />

<h2>Click yes to bypass prompt below</h2>
![image](https://github.com/Bybburnam/resource-groups-virtual-machines/assets/102566114/09b554e2-5d42-4870-aecd-d8205d68f24e)
<br />
<br />

<h1>Congrats, you have made your first Virtual Machine with Microsoft Azure</h1>

![image](https://github.com/Bybburnam/resource-groups-virtual-machines/assets/102566114/d8637853-1fa7-49f0-8e09-9135ae9fd4f0)
