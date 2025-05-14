# azure-networking-firewall-bastion-handson
Hands-on project deploying a secure web application environment in Azure using Firewall and Bastion.

This hands-on project demonstrates the deployment of a secure web application environment in Microsoft Azure, following a practical walkthrough. The goal was to understand and implement network segmentation and secure access using key Azure networking services.

## Key Azure Services Used

* **Azure Virtual Network (VNet):** The foundational private network in Azure, segmented into subnets for the Azure Firewall and the web application.
* **Azure Firewall:** A managed, cloud-based network security service used to control inbound and outbound traffic to the VNet and its resources.
* **Network Security Groups (NSGs) (Implicit):** While not explicitly the focus, NSGs likely played a role in controlling traffic at the subnet and network interface levels.
* **Azure Virtual Machine (VM):** An Ubuntu VM deployed in a private subnet to host the web application.
* **Nginx:** A web server installed on the VM to serve a basic static HTML page.
* **Azure Bastion:** Provided secure, agentless SSH access to the private VM directly from the Azure portal.


## What the Project Demonstrates

This project showcases how to:

* Create a basic Azure network infrastructure with a Virtual Network and subnets.
* Implement a centralized network security perimeter using Azure Firewall.
* Securely host a web application VM without exposing it directly to the public internet.
* Utilize Azure Bastion for secure management and access to VMs within a private network.
* Configure basic firewall rules to allow access to the web application.
* Understand the concepts of network segmentation and secure remote access in Azure.

![Screenshot 2025-05-14 093533](https://github.com/user-attachments/assets/57b505fd-6034-432a-b141-791bc56e7719)





![Screenshot 2025-05-14 110310](https://github.com/user-attachments/assets/f4190210-6601-46d5-8d71-d7e11792ca33)





![Screenshot 2025-05-14 110730](https://github.com/user-attachments/assets/ddba4a4a-b02c-45b9-ab12-07e136aeba7e)





![Screenshot 2025-05-14 152050](https://github.com/user-attachments/assets/7a4a3f7f-f2c2-409a-80a6-02571cbfd9da)





![pic](https://github.com/user-attachments/assets/7ea1a94a-adbd-4791-8407-5ebf88788f9a)
