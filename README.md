<p align="center">
<img src="https://www.logo.wine/a/logo/Microsoft_Azure/Microsoft_Azure-Logo.wine.svg" alt="Azure Logo" />
</p>

# Creating a Virtual Machine in Azure
This tutorial outlines the installation of a Virtual Macine in Microsoft's Azure<br />

## Environments and Technologies Used

- Microsoft Azure
- Remote Desktop Protocol

## Operating Systems Used

- Windows 10</b> (21H2)

## List of Prerequisites

- Microsoft account
- Internet connection

## Installation Steps
1. Go to the [Azure](https://portal.azure.com) portal and create a resourse group (resoures groups are a way to help organize your Azure services)

![resource groups](https://github.com/ColinGMatherne/Azure-VM/assets/132864551/66f48d67-5a79-43d2-9453-d8c7b209f3b1)
## 
![Create RG](https://github.com/ColinGMatherne/Azure-VM/assets/132864551/e6583522-7ff8-4eee-86d0-434e2b5adef2)

After navigating to the resourse group creation page, just enter the name you want and click "Review + create"

![Name and tags](https://github.com/ColinGMatherne/Azure-VM/assets/132864551/81c38638-15d0-45c4-9b4b-bd6f6dd5f1f1)

2. Go to the Virtual Machines service, and set subscription, group, name, image, username and password

![VMs](https://github.com/ColinGMatherne/Azure-VM/assets/132864551/a82c9eae-7b48-4285-a24f-96945b4b7944)
## 
![Create VM](https://github.com/ColinGMatherne/Azure-VM/assets/132864551/e650f89b-fce3-4b65-be1f-cc5df587d383)
## 
![VM Config 1](https://github.com/ColinGMatherne/Azure-VM/assets/132864551/68f45429-610d-47f7-84c2-335f5c66f605)
## 
![VM Config 2](https://github.com/ColinGMatherne/Azure-VM/assets/132864551/95e6c0e7-17c8-4898-b510-1af3f53c057b)

- The subscription is the account that will be charged for the resourses
- Set the "Resource group" to the one you created earlier
- The image is the OS/iso file you would like to use
- Size is the resources you would like to use (2vcpu 16 Gib used in this example)
- If you would like to change the network settings, just click next twice anc you can confiure it there (out of scope)

  After finishing with the creation of the VM go back to the VM service page, click on your VM, then copy the public IP address

  ![Pub IP](https://github.com/ColinGMatherne/Azure-VM/assets/132864551/effa8b3d-df83-4ade-a6b6-b7f36634247b)

After copying the IP address open Remote Desktop Protocol, enter the IP address, click connect then enter the username and password

![RDP](https://github.com/ColinGMatherne/Azure-VM/assets/132864551/de368a50-c6ca-4c68-a2d4-bcd498f493ad)

After clicking "OK" you should then be connected to the VM and able to use it as a regular computer
