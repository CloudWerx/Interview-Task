```bash

█▀▀ █░░ █▀█ █░█ █▀▄ █░█░█ █▀▀ █▀█ ▀▄▀
█▄▄ █▄▄ █▄█ █▄█ █▄▀ ▀▄▀▄▀ ██▄ █▀▄ █░█
```
# Cloudwerx Interview Task

## Part 1 - IAC Creation

A part of every engineers routine is to create infrastructure based on the architects requirements, and a solutions architect has given you the following task:
### You must create a Terraform deployment script that achieves the following requirements:

1. Private CloudSQL Db (Postgres or Mysql)
2. Private GKE cluster on a dedicated VPC (not default VPC)
3. Build and Deploy a sample application on the above GKE
4. Configure Workload Identity for the GKE cluster
5. Establish GKE and Private SQL connecting with SQL Auth Proxy using a sidecar container
6. Establish CI/CD pipeline (CloudBuild/CloudDeploy, Github Actions or any tools)
7. Expose the sample application via Gateway Controller(GKE)

### Overarching theme

* Ensure proper security controls are in place
* Ensure autoscale for the application

Explain why you chose your application and how it interacts with the SQL Database and the networking layers. Please note that the application deployment must be done within terraform such that applying terraform is sufficient in configuring the application as well.


### Bonus Points

1. Creating a Terraform module for the task
2. Drawing the architecture diagram
3. Documentation

Any engineer that is a good problem solver should also be capable of explaining the solution architecture through clean documentation!

## Part 2 - Infrastructure 

A fellow engineer has asked you to help them document and improve the terraform codebase they just created, and you are required to do the following tasks:

1. Document all files in the Terraform folder in this repository

## Good Luck and thank you for your time!

You may submit the solution to these problems by cloning this repository, adding your solutions and pushing it to a personal public repositry and send it to us.