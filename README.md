**Ticket Type:** Task  
**Title:** Create a New GitHub Repository  
**Project:** Version Control System Deployment  
**Assignee:** You  
**Reporter:** Derek Morgan  
**Priority:** High  
**Labels:** Terraform, AWS, VPC  
**Epic Link:** GitHub Expansion  
**Sprint:** Sprint 01/Resources

**Description:**

Your team needs a new repository to store your Terraform code. Deploy a GitHub Repository called "dev-repo" with a description of "Development Repo", set it to auto-initialize, and add a .gitignore template for Terraform. 

**Acceptance Criteria:**

> **Note:** If the `terraform validate` command fails, all tasks in the lab will fail!

If you need to authenticate to GitHub to deploy the repository, you can run this command from your Codespace:

<!-- font-size: 16px -->
```bash
unset GITHUB_TOKEN && gh auth login -h github.com -p https -s delete_repo -w
```

**Implementation Notes:**

- <a href="https://registry.terraform.io/providers/integrations/github/latest/docs" target="_blank">GitHub Provider Documentation</a>  
- <a href="https://developer.hashicorp.com/terraform/language/resources" target="_blank">Terraform Documentation</a>
