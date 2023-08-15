# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

Virtual Machine is an Azure Infrastructure as a Service (IaaS) is a type of cloud computing service that provide full access to the underlying operating system of a compute resource. These can be either Windows or Linux machines, with great availability, scalability and redundancy. These require more on-going maintenance and up-keep by cloud developers.
 
App Service is an Azure Platform as a Service (PaaS) is a type of cloud computing service that allow developers to focus more on their apps than the underlying infrastructure i.e Azure takes care of the infrastructure. It is an HTTP-based service for hosting web applications, REST APIs, and mobile back ends. It supports multiple languages and continuous deployment.

I would prefer to select an app service for deploying the final project because it is more cost-effective and simpler to deploy compared to a virtual machine. The final project utilizes Python, which is already supported by the app service, eliminating the need for me to use a virtual machine and handle all installations manually.

Cost: Azure App Service is like a cheaper choice compared to Virtual Machines. It offers different plans, including free ones, which are great for trying out or launching apps. Plus, it helps save money on the technical stuff.

Scalability: Azure lets me make my apps bigger or smaller easily. It's like giving my app more space when it's busy or using less when it's not. I can set it up to do this on its own, like getting more seats at a table when more friends come over.

With Auto Scaling, my app can grow or shrink on its own, like getting more helpers when things get busy.

Availability: Azure App Service makes sure my app is available to people everywhere. It's like having my app in different parts of the world, so if there's a problem in one place, people can still use my app somewhere else. The App Service promises my app will almost always be ready to use.

Workflow: Azure App Service makes putting my app on the internet super simple. It can update my app automatically from places like GitHub or Azure DevOps. It's like having a team that helps my app get online without any fuss.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

I would like to use virtual machines in the future when I need full control over the operating system to install software on the server, especially if the project switches to another language that the app service does not support.