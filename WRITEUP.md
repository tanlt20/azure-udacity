# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*


 Virtual Machine is an Azure Infrastructure as a Service (IaaS) is a type of cloud computing service that provide full access to the underlying operating system of a compute resource. These can be either Windows or Linux machines, with great availability, scalability and redundancy. These require more on-going maintenance and up-keep by cloud developers.
 
App Service is an Azure Platform as a Service (PaaS) is a type of cloud computing service that allow developers to focus more on their apps than the underlying infrastructure i.e Azure takes care of the infrastructure. It is an HTTP-based service for hosting web applications, REST APIs, and mobile back ends. It supports multiple languages and continuous deployment.

I would prefer to select an app service for deploying the final project because it is more cost-effective and simpler to deploy compared to a virtual machine. The final project utilizes Python, which is already supported by the app service, eliminating the need for me to use a virtual machine and handle all installations manually.
### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

I would like to use virtual machines in the future when I need full control over the operating system to install software on the server, especially if the project switches to another language that the app service does not support.