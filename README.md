# Azure-Projects
Azure Project 1
Cloud based file share and sync solution:
Implemented a cloud-based scalable and secure file share and sync solution using Azure services. The solution can be easily scaled up to run in your data center or on a public cloud, with its servers, storage etc. completely managed and controlled by your IT team in accordance with a company’s governance and security requirements.

Skills and Tools
Virtual Machines, Virtual Networks, Network Security Group, DBserver MySQL, Appserver Bashion
Scenario

According to recent research, 40-75% of employees are using Dropbox to share files inside and outside of their businesses. Half of those Dropbox users do this even though they know it's against the rules. More than 40% of businesses have experienced the exposure of confidential information and the estimated average cost of a data breach equaled $5.5 Million in 2011.

These files, containing sensitive company and customer data, are stored in a public cloud outside of the businesses' control - possibly even outside of the country. The potential for data leakage and security breaches is enormous and companies need to stay compliant with their own policies and procedures for security and governance

Architecture Implementation
Implement 2 different subnets (one public and the other private) in a virtual network
Install and configure MySQL on an Ubuntu 18.04 virtual machine on the private subnet using the instructions provided. (Hint: Use a bastion host and a NAT gateway)
Install and configure OwnCloud on an Ubuntu 18.04 virtual machine on the public subnet using the provided instructions.
Configure the network security groups to allow the required ports
Test the installation by accessing the IP of the application server in a browser 

Azure Project 2


Building an Automated Business Process using Managed Services on a Public Cloud
Course Microsoft Azure
In the connected world, it is imperative that the organizations be interlinked with the customers and vendors. This process has been very sluggish, manual, batch-based and prone to failures. Such Integration design has lead to impaired decision making and delays in the detection of fraudulent actions. This project created an automated, event-based real-time process using managed cloud services that do not have these limitations.
Skills and Tools
Azure VM, Python, Blob Storage, Azure SQL, Azure SDK for Python
Architecture Implementation
1	Upload the custom program and provided text file to a VM created using Ubuntu
2	Create a MySQL server using Azure Database service
3	Create a database inside the MySQL server created above
4	Running the custom program will convert the text file into a CSV file, upload it to blob storage and send the data to the MySQL server.
