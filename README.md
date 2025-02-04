# PythonAPI-Automation
**Experiment Overview**
This experiment focuses on deploying and managing infrastructure and applications using Terraform, Python integration, and AWS services. The setup involves multiple modules and repositories for provisioning, continuous delivery, and automation workflows.

**Repositories**

**JenkinsComplex**

Demonstrates Terraform provisioning for a Jenkins CI/CD pipeline setup.

**Highlights:**

--> Infrastructure as Code (IaC) with Terraform.

--> Jenkins setup on AWS EC2 instances.

**Python_ContinuousDelivery**

Automates application deployment using Python scripts and continuous delivery workflows.

**Highlights:**

--> Integration of Python scripts for deployment.

--> Continuous delivery pipeline setup.

**ProvisionAppServer**

Provisions application servers on AWS EC2 using Terraform.

**Highlights:**

--> Server provisioning and configuration.

--> Application hosting on provisioned servers.

**Experiment Steps**

**1. Infrastructure Provisioning**

* Terraform is used to provision AWS EC2 servers.

* The output includes server details and IP addresses.

**2. Python Integration and Deployment**

* Python scripts are executed to deploy the application.

* Console outputs from Python integration are captured to verify deployment success.

**3. Validation**

* Use curl commands to validate application deployment.

* Output from the curl command ensures the application is accessible.

**Outputs**

**Terraform Apply Output:**

--> Shows successful infrastructure provisioning.

--> Displays AWS EC2 instance details (IP addresses, server IDs).

**Python Integration Console Output:**

--> Logs from Python scripts confirming successful integration and deployment.

**Deployment Validation:**

--> Application accessible via curl commands.

**Tools Used**

* Terraform: For infrastructure provisioning.

* Python: For automation and deployment.

* AWS EC2: For hosting servers and applications.**
