<p align="center">

</p>

Inspecting Network and ICMP Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe icmp and network traffic to and from Azure Virtual Machines with Wireshark. <br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Command-Line Tools
- Network Protocol (ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Step 1 Log into Windows virtual machines
- Step 2 Download and Install Wireshark
- Step 3 Open Wireshark to analyze Network traffic
- Step 4 Open PowerShell to ping the linux virtual machine from within the windows virtual machine and use wireshark to analyze icmp traffic

<h2>Actions and Observations</h2>

<p>

1. Log into your windows virtual machine
1.a Double click Microsoft Edge inside of your virtual machine
![WireShark](https://github.com/user-attachments/assets/07369448-e383-4db2-b048-6ff9aee47591)

1.b In the search bar type wireshark.org 1.c Click the www.wireshark.org
![WireShark2](https://github.com/user-attachments/assets/f057a33a-5af1-465b-a32a-3ad454f34aa9)
 1.d At the to click on Download
![WireShark3](https://github.com/user-attachments/assets/cc2727fd-9189-4978-be5e-7b8aa02c5ee5)

1.e Click on Windows x64 Installer to download once downloaded run the wireshark installer
![WireShark4](https://github.com/user-attachments/assets/58b55fa9-7a93-496a-8d59-73099c5bb5fb)

1.f click next, noted, next, next, next, next, next, install I Agree, install, next, finish, next, finish
![WireShark6](https://github.com/user-attachments/assets/292014f9-bfb0-475a-b006-85514a8ed06c)

1.g Go to the start menu in your windows virtual machine and type Wireshark and click on the    Wireshark app
![WireShark7](https://github.com/user-attachments/assets/b1c287df-920f-4f5e-b7ea-c55951cc75e4)

1.h Inside of the wireshark network analyzer highlight Ethernet
![WireShark8](https://github.com/user-attachments/assets/a4eace7c-84ef-4c6c-aebc-cee7c6e86ee9)

1.i click on the blue shark fin and now you should be able to see the traffic "happening over the Network
![WireShark9](https://github.com/user-attachments/assets/b643de53-1252-43ba-8144-62230b304e8e)




![ICMP](https://github.com/user-attachments/assets/ed3986c9-63c3-4ae2-9a61-7830c3a6cf89)

![ICMP1](https://github.com/user-attachments/assets/d5bb216d-bb22-41d9-803a-d21f6fd78cd1)

![ICMP2](https://github.com/user-attachments/assets/54371fac-5328-44a5-9c0a-736b9c453162)

![ICMP3](https://github.com/user-attachments/assets/12edcdbb-fe45-43b6-a1ca-80d1b3131beb)









