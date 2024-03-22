<h1>Creating Virtual Machines Using Microsoft Azure Cloud Platform</h1>

![image](https://github.com/patrickoigwilo/My-CourseCareers-FinalExam-Project/assets/162601853/2d70d06c-1917-4cc8-a580-fa4cf4d9ed40)


<h2>Project Summary:</h2>
This project shows how I created 2 (two) virtual machines on the Microsoft Azure cloud compute platform.<br>
One of the virtual machines ran a Microsoft Windows 10 operating system, while the other ran a Linux Ubuntu operating system.


![image](https://github.com/patrickoigwilo/My-CourseCareers-FinalExam-Project/assets/162601853/eb29e7bb-2870-45ed-89bb-3339b32aa101)

<h2>Video Demonstration:</h2>

- [How to Create Virtual Machines with Microsoft Azure](https://www.youtube.com)
  

<h2>Environments, Applications and Technologies Used:</h2>

- Microsoft Azure cloud platform
- Microsoft Windows 10 (21H2)
- Linux Ubuntu 20.04
- Remote Desktop
- Powershell/CLI

<h2>Walk-through:</h2>

- I created a resource group from my Microsoft Azure tenant and subscription account.
- (A resource group is a container that holds all the computing resources, for the virtual machines in this case, including the virtual network, subnet, unique Network Interface Card; NIC, private and public IP addresses and Network Security Group (NSG) which essentially is a firewall for screening network traffic.)
- I created a virtual network inside my resource group.
- I also created a subnet inside my virtual network.
- The two virtual machines - one Windows 10 and the other Linux Ubuntu with automatically assigned NSGs - were created inside the subnet. Each virtual machine has both a private and public IP address. The public IP address is used to connect to the world wide web while the private IP address is used to connect between virtual machines.
