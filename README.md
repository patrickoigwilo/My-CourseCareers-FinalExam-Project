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
- Microsoft Windows 10 Pro (22H2)
- Linux Ubuntu Server 20.04
- Microsoft Remote Desktop
- Powershell/CLI

<h2>Walk-through:</h2>

- I created a resource group from my Microsoft Azure tenant and subscription account.
- (A resource group is a container that holds all the computing resources, for the virtual machines in this case, including the virtual network, subnet, unique Network Interface Card; NIC, private and public IP addresses and Network Security Group (NSG) which essentially is a firewall for screening network traffic.)
- Next, I created the 2 virtual machines - one after the other. When a virtual machine is created in Azure, other components such as the virtual network and subnet, NICs, IP addresses and NSGs are automatically created.
- (The two virtual machines - one Windows 10 and the other Linux Ubuntu with automatically assigned NSGs - were created inside the virtual network and subnet. Each virtual machine was assigned both a private and public IP address. The public IP address is used to connect publicly to and from the World Wide Web while the private IP address is used to connect privately between virtual machines.)
- Finally, I used Microsoft Remote Desktop to access the Windows virtual machine (VM1) from my host computer; from VM1, I pinged VM2 (Ubuntu virtual machine) using Powershell and got a response from VM2.
- Please, see the attached screenshots below:
</br>

![image](https://github.com/patrickoigwilo/My-CourseCareers-FinalExam-Project/assets/162601853/bd63885f-491b-4a23-a18b-a947487f94b2)

![image](https://github.com/patrickoigwilo/My-CourseCareers-FinalExam-Project/assets/162601853/39c82d5a-fa33-49bf-aaaa-9c4763a2b062)

![image](https://github.com/patrickoigwilo/My-CourseCareers-FinalExam-Project/assets/162601853/9504575b-3e79-4d17-bf80-47fca22fe078)

![image](https://github.com/patrickoigwilo/My-CourseCareers-FinalExam-Project/assets/162601853/748181df-58ed-409f-9d48-29ed96578115)

![image](https://github.com/patrickoigwilo/My-CourseCareers-FinalExam-Project/assets/162601853/7c35dced-87de-4aea-bd7d-e3ea54bc3c60)

![image](https://github.com/patrickoigwilo/My-CourseCareers-FinalExam-Project/assets/162601853/268c8f13-6992-4fad-b44c-49d0de938226)

![image](https://github.com/patrickoigwilo/My-CourseCareers-FinalExam-Project/assets/162601853/d43dec1b-1f6f-41bd-ab9c-d3d5ebf73eb1)

![image](https://github.com/patrickoigwilo/My-CourseCareers-FinalExam-Project/assets/162601853/cb070d4a-0dbb-4e2f-8ced-13fbb8a98368)

![image](https://github.com/patrickoigwilo/My-CourseCareers-FinalExam-Project/assets/162601853/10e7ad4a-178b-4003-9737-a6c8befd30b2)

