**Ticket Type:** Task  
**Title:** Create an AWS VPC Resource  
**Project:** Cloud Infrastructure Deployment  
**Assignee:** You  
**Reporter:** Derek Morgan  
**Priority:** High  
**Labels:** Terraform, AWS, VPC  
**Epic Link:** AWS Infrastructure Expansion  
**Sprint:** Sprint 01/Resources

**Lab Setup**
This lab uses Localstack to simulate an AWS environment. Localstack is already preinstalled in your environment. You don't need keys or to configure the provider. If you'd like to use your own account, feel free to specify your provider configuration and run `unset aws` and `unset terraform` to decouple them from Localstack.

**Description:**

Your team needs to set up a new Virtual Private Cloud (VPC) in AWS to host your application infrastructure. Create a VPC called "dev-vpc" with a CIDR block of "10.0.0.0/16", enable DNS support and DNS hostnames, and tag it with "Environment" = "Development".

**Acceptance Criteria:**

1. Create a VPC resource named "dev-vpc" with CIDR block "10.0.0.0/16"
2. Enable DNS support for the VPC
3. Enable DNS hostnames for the VPC
4. Tag the VPC with "Environment" = "Development"

> **Note:** If the `terraform validate` command fails, all tasks in the lab will fail!

**Implementation Notes:**

- <a href="https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/vpc" target="_blank">AWS VPC Resource Documentation</a>  
- <a href="https://developer.hashicorp.com/terraform/language/resources" target="_blank">Terraform Resources Documentation</a>  
- <a href="https://developer.hashicorp.com/terraform/language/providers/configuration" target="_blank">Terraform Provider Configuration</a>
