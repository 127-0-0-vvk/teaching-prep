# Azure Networking

### Questions

| Can Answer? | # | Question |
| --- | --- | --- |
| <input type="checkbox"> | 1 | What is Networking used for in Azure? |
| <input type="checkbox"> | 2 | What is Virtual (private) Network? |
| <input type="checkbox"> | 3 | What is VNet Peering? |
| <input type="checkbox"> | 4 | What is Azure Load Balancer? |
| <input type="checkbox"> | 5 | What is Azure VPN Gateway? |
| <input type="checkbox"> | 6 | What is Azure Express Route? |
| <input type="checkbox"> | 7 | What is Content Delivery Network (CDN)? |
| <input type="checkbox"> | 8 | What is caching in networking? |
| <input type="checkbox"> | 9 | What is Azure Application Gateway? Is it used for IP or DNS routing? |
| <input type="checkbox"> | 10 | What is Azure Traffic Manager? |
| <input type="checkbox"> | 11 | What are the 7 layers of networking? |

### Answers


1)Networking in Azure is used to establish communication between various resources, services, and users within the Azure cloud environment. It enables secure and reliable data transfer between virtual machines, containers, databases, and other Azure services. Azure networking also provides connectivity between on-premises networks and the Azure cloud, facilitating hybrid cloud scenarios.


2)A Virtual Network (VNet) is a logically isolated network in Azure that allows you to securely connect and isolate Azure resources. It provides IP address space, subnets, and network security groups to define communication rules between resources within the VNet. VNets can be extended to on-premises networks through VPN or ExpressRoute connections.


3)VNet Peering is a mechanism that allows connecting two Azure VNets directly without the need for a gateway or additional hardware. It enables resources in one VNet to communicate with resources in the peered VNet as if they were in the same network, providing low-latency and high-bandwidth communication.


4)Azure Load Balancer is a traffic distribution service that evenly distributes incoming network traffic across multiple virtual machines or services. It enhances high availability and fault tolerance by distributing traffic and resources efficiently, ensuring optimal performance and preventing overloading of individual resources.


5)Azure VPN Gateway is a service that allows you to establish secure and encrypted connections between your on-premises network and Azure Virtual Network. It enables you to create Site-to-Site (S2S) VPN connections or Point-to-Site (P2S) VPN connections to access Azure resources securely.


6)Azure ExpressRoute is a private, dedicated network connection between on-premises networks and Microsoft Azure data centers. It offers a more reliable and predictable connection compared to a public internet connection, providing higher security and lower latency for data transfers.


7)A Content Delivery Network (CDN) is a distributed network of servers located in multiple data centers worldwide. It caches and delivers web content, such as images, videos, and static files, from the nearest server to the end-users. This reduces latency and improves the performance of web applications, especially for geographically dispersed users.


8)Caching in networking refers to the temporary storage of frequently accessed data closer to the user or application, reducing the need to fetch the data from the original source repeatedly. Caching improves data retrieval speed, reduces network traffic, and enhances overall performance.


9)Azure Application Gateway is a layer 7 load balancer that provides application-level routing and load balancing services. It is used for DNS-based routing, forwarding requests to different backend pools based on hostnames or URL paths. It supports features like SSL termination, cookie-based affinity, and Web Application Firewall (WAF).


10)Azure Traffic Manager is a DNS-based global load balancer that distributes incoming traffic across multiple endpoints in different Azure regions or external endpoints. It helps improve application availability, responsiveness, and fault tolerance by directing users to the nearest or best-performing endpoint.


11)The 7 layers of networking, as defined in the OSI (Open Systems Interconnection) model, are:

Physical Layer
Data Link Layer
Network Layer
Transport Layer
Session Layer
Presentation Layer
Application Layer






## Virtual Networks (VNets)

### Exercises

Exercise: 🚀 Creating a VM in an existing VNet and connecting to it
Step 1: 🌐 Create a Virtual Network (VNet) using Azure Portal
Sign in to the Azure Portal (https://portal.azure.com).
🖋️ Click on "+ Create a resource" in the left-hand menu.
🔍 Search for "Virtual network" in the search bar and select "Virtual network" from the results.
🏁 Click "Create" on the Virtual network blade.
📝 Fill in the required details for the VNet, such as Name, IP address range, and Subnet name.
✅ Click "Create" to create the VNet.
Step 2: 🕸️ Create a Subnet for the existing VNet
📝 Navigate to the newly created VNet in the Azure Portal.
📝 In the VNet overview page, click on "Subnets" in the left-hand menu.
📝 Click on "+ Subnet" to add a new subnet.
📝 Provide a Name for the new subnet and set its Address range.
✅ Click "OK" to create the subnet.
Step 3: 🖥️ Create a Virtual Machine (VM) in the Subnet
🖋️ Click on "+ Create a resource" in the left-hand menu.
🔍 Search for "Windows Server" or "Linux" depending on your preference and select the desired image from the results.
🏁 Click "Create" on the VM blade.
📝 Fill in the required details for the VM, such as Name, Region, Resource group, and Size.
📝 Under the "Networking" section, select the existing VNet and Subnet created earlier.
📝 Set up an Administrator account and configure any additional settings as needed.
✅ Click "Review + create" and then "Create" to deploy the VM.
Step 4: 🤝 Connect to the VM using SSH (Linux) or RDP (Windows)
For Linux VM (SSH):
🔍 Once the VM is deployed, navigate to the VM's overview page in the Azure Portal.
🔍 In the overview page, click on "Connect" to get the SSH command for connecting to the VM.
🚀 Open a terminal on your local machine and use the provided SSH command to connect to the VM.
For Windows VM (RDP):
🔍 Once the VM is deployed, navigate to the VM's overview page in the Azure Portal.
🔍 In the overview page, click on "Connect" to download the RDP file for connecting to the VM.
🚀 Open the downloaded RDP file, enter the credentials you set up during VM creation, and connect to the VM.
Congratulations! 🎉 You have now successfully created a VM in an existing VNet and connected to it using SSH (Linux) or RDP (Windows) through the Azure Portal.

Note: Make sure to properly manage your Azure resources to avoid unnecessary costs. Don't forget to stop or deallocate the VM when not in use.










## VNet Peering

### Exercises

| Done? | # | Exercise |
| --- | --- | --- |
| <input type="checkbox"> | 1 | Create two VNets (with non-overlapping addresses) with one VM deployed to each. Only one VM should have public IP address. |
| <input type="checkbox"> | 2 | Setup Network Peering between two VNets. |
| <input type="checkbox"> | 3 | Connect (SSH/RDP) to the VM with the public IP from your laptop. From it, connect to the other VM using its private IP. |
