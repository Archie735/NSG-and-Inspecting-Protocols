<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connect
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 11 
- Ubuntu Server 

<h2>Prequisite</h2>
* Complete <a href=https://github.com/Archie735/How-to-Create-a-Windows-11-Virtual-Machine/blob/main/README.md> Windows 11 </a> virtual machine first before creating Ubuntu Server

<h3>Create a Linux Virtual Machine</h3>
Search for Virtual Machine then Create "Azure Virtual Machine"
Copy the information below ↓

    Subscription: Azure subscription 1
    Resource group: Seasons
    Virtual machine name: Summer
    Region: (US) East US
    Image: Ubuntu Server 22.04 LTS – x64 Gen 2
    Size: Ubuntu Server 22.04 LTS – x64 Gen 2
    Authentication type: Password
    Username: Summerfield
    Password: Summerfestival2
    Virtual network: Winterland-vnet
    Review + create then Create

    

![Step 3 vpn](https://github.com/Archie735/How-to-Create-a-Windows-11-Virtual-Machine/assets/150314129/4037d684-4375-4f25-9e87-96799e5543b0)


![Step 4 vpn](https://github.com/Archie735/How-to-Create-a-Windows-11-Virtual-Machine/assets/150314129/4afff7b8-33ad-423a-afc7-0994bfbd3593)


![Step 5 vpn](https://github.com/Archie735/How-to-Create-a-Windows-11-Virtual-Machine/assets/150314129/6c7d73bf-1d97-46c0-ac61-b25dc5a8d3f3)


* You can modify the resource group, virtual machine name, region, username, and password to your liking ;)

<h3>Connect to Windows 11 through Remote Desktop Connect</h3>

<h3>Download WireShark on Windows 11 Virtual Machine</h3>

  * On the virtual machine type <a href=https://www.wireshark.org/download.html> Wireshark Download </a> on the edge browser
  * Install Windows x64 Installer on default settings
  * Click I agree
  * Finish


![Step 9 vpn](https://github.com/Archie735/How-to-Create-a-Windows-11-Virtual-Machine/assets/150314129/b838e296-f61f-4d90-8b2f-25895b7c185d)


<h3 align="center"><ins>Observe ICMP Traffic</ins></h3>

<h3 align="center"><ins>Observe SSH Traffic</ins></h3>

<h3 align="center"><ins>Observe DHCP Traffic</ins></h3>

<h3 align="center"><ins>Observe DNS Traffic</ins></h3>

<h3 align="center"><ins>Observe RDP Traffic</ins></h3>
