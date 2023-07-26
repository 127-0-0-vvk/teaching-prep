# Azure Resource Manager (ARM) Templates

### Questions

| Can Answer? | # | Question |
| --- | --- | --- |
| <input type="checkbox"> | 1 | What ARM templates are used for? | 
| <input type="checkbox"> | 2 | What file format ARM templates use? |
| <input type="checkbox"> | 3 | What Azure Resource Manager does? |
| <input type="checkbox"> | 4 | Why use ARM templates instead of deploying resources through portal? |
| <input type="checkbox"> | 5 | Do ARM templates use Declarative or Imperative syntax? What's the difference? |

### Answers
1) ARM templates are used for deploying and managing resources in Azure. They are JSON (JavaScript Object Notation) files that define the infrastructure and configuration of Azure resources required for an application or solution. ARM templates can include a wide range of resources like virtual machines, storage accounts, virtual networks, web apps, databases, and more.

2) ARM templates use the JSON (JavaScript Object Notation) file format. JSON is a lightweight data interchange format that is easy for both humans and machines to read and write.

3) Azure Resource Manager (ARM) is the deployment and management service for Azure. It provides a unified management layer that allows you to create, update, and delete resources in your Azure subscription. ARM enables consistent management of resources and their dependencies, supports role-based access control (RBAC), and provides features like resource tagging, monitoring, and auditing.
4) There are several reasons to use ARM templates instead of deploying resources through the Azure portal:

a. Consistency and Repeatability: ARM templates allow you to define your infrastructure as code, making deployments consistent and repeatable. This means you can easily recreate the same environment in multiple instances, such as development, staging, and production.

b. Version Control: ARM templates can be stored in version control systems, providing a history of changes and the ability to roll back to previous versions if needed.

c. Automation: ARM templates can be used in conjunction with CI/CD pipelines and other automation tools to streamline the deployment process and reduce manual intervention.

d. Infrastructure as Code (IaC): ARM templates embrace the concept of IaC, which treats infrastructure configuration as code. This approach brings many benefits, such as code reviews, collaboration, and easier troubleshooting.

e. Scalability: For complex deployments with multiple resources, ARM templates provide a more efficient and scalable way to manage and deploy resources.

5) ARM templates use Declarative syntax. Declarative syntax means you define the desired state of the resources without specifying the step-by-step procedures to achieve that state. In other words, you declare what resources you want to be provisioned and configured, and Azure Resource Manager takes care of figuring out the necessary steps to reach that desired state.
