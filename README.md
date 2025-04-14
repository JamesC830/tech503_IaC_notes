# Infrastructure as code notes

***Infrastructure as code (IaC)***: the managing and provisioning of infrastructure through code instead of through manual processes

- ***Configuration files are created that contain your infrastructure specifications***, which makes it easier to edit and distribute configurations. It also ensures that you provision the same environment every time
- ***Divide your infrastructure into modular components*** that can then be combined in different ways through automation

## Approaches:
- ***Declarative***: 
  - ***Defines the desired state of the system***, including what resources you need and any properties they should have, and an IaC tool will configure it for you
  - ***Keeps a list of the current state of your system objects***, which makes taking down the infrastructure simpler to manage
- ***Imperative***: 
  - ***Defines the specific commands needed to achieve the desired configuration***, and those commands then need to be executed in the correct order

## Benefits:
- ***Cost reduction***
- ***Increase in speed of deployments***
- ***Reduce errors***: Manual configuration is error-prone due to human involvement
- ***Improve infrastructure consistency***: Environments can be easily duplicated
- ***Eliminate configuration drift***: Where a system's actual configuration deviates from its desired state, often due to incremental changes or manual adjustments
- ***Automation***: Automates provisioning tasks
- ***Iterate on best-practice environments***: Easily build and branch on environments

## Role in DevOps:

- Quickly set up complete environments, from development to production
- Help ensure consistently reproducible configurations between environments
- Integrate seamlessly with cloud providers and efficiently scale infrastructure resources up or down based on demand

## Tools:

- **Ansible**: Open source IT automation engine that automates provisioning, configuration management, application deployment, orchestration, and many other IT processes
- **Terraform**: Infrastructure as code tool that lets you define both cloud and on-prem resources in human-readable configuration files that you can version, reuse, and share. You can then use a consistent workflow to provision and manage all of your infrastructure throughout its lifecycle. Terraform can manage low-level components like compute, storage, and networking resources, as well as high-level components like DNS entries and SaaS features