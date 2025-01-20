# 2025-01-20
- Abhishek KC, Kcabhishek23, amk1002865@student.hamk.fi 

### Create an Azure Account:
- First of all By using HAMK ID we create Microsoft Azure accounnt.
- By using University Mail ID It gives worth upto $100.

![layer1](image/Slide%201.jpg)

### Create a Virtual Machine:
- I created a new resource group in Azure portal.
- I created a new virtual machine in Azure portal. ( It may take some time to load)
- I selected North Europe as a Region and Ubuntu Server 24.04 LTS - x64 Gen2 as the operating system.
- I selected the virtual machine size as Standard_B2ls_v2- 2 vCPUs, 4 GiB Memory ($33.29/month).
- I selected the network configuration as Public IP address and Network interface and created a new Username.
- seleceted OS disk type as Standard SSD and Storage type as Locally-redundant storage.
- I selected the public IP address as Static and created a new public IP address as lab-robotics-ip.
- I selected inbound ports as (Http(80), HTTPS(443), SSH(22))
- I selected the Enable auto-shutdown and set the auto-shutdown time as 10:00 PM and Select the time Zone as (UTC + 2:00) Helsinki
- I reviewed the settings and created the virtual machine.

![layer2](image/slide%202.jpg)

### Connect to the VM:
- After that the Virtual Machine is successfully created.
- Goto the file we create in VM and in the left sidebar of the settings section click "Configuration" from there we see DNS name label (optional) we can write a name in that label.
- After that We also have to go Connect which in the left side bar of the connect section click "Connect" and that click "Native SSH - Select" and after we have to past path of the file we downloaded when our virtual machine is created and paste in to "Copy and execute SSH command" and from the bottom of that we copy the SSH to VM with specified private key.

![layer2](image/slide%203.jpg)

### Run the Terminal
- Paste that specified private key in the terminal.

![layer2](image/slide%204.jpg)