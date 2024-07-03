# Week 4: Terraform and CI/CD with GitHub Actions

## Activity 1: Terraform Basics
**Goal:** Understand infrastructure as code with Terraform.
**Description:** Introduction to Terraform and its basic concepts.

**Tasks:**
1. Install Terraform.
2. Write a Terraform configuration to provision a simple infrastructure (e.g., a VM instance on GCP).
3. Use `terraform init`, `terraform plan`, and `terraform apply`.
4. Explore `terraform state` and `terraform destroy`.
5. Manage Terraform configurations using modules.

**References:**
- [Terraform Documentation](https://www.terraform.io/docs/index.html)
- [Getting Started with Terraform](https://learn.hashicorp.com/terraform)

## Activity 2: Advanced Terraform
**Goal:** Manage complex infrastructures with Terraform.
**Description:** Learn advanced Terraform features and best practices.

**Tasks:**
1. Use variables and outputs in Terraform configurations.
2. Implement resource dependencies and lifecycle management.
3. Manage remote state with Terraform Cloud or backend storage.
4. Use workspaces for environment management.
5. Implement a CI/CD pipeline for Terraform using GitHub Actions.

**References:**
- [Terraform Variables](https://www.terraform.io/docs/configuration/variables.html)
- [Terraform State](https://www.terraform.io/docs/state/index.html)

## Activity 3: Introduction to CI/CD with GitHub Actions
**Goal:** Understand CI/CD principles and GitHub Actions.
**Description:** Brief introduction to CI/CD concepts and GitHub Actions.

**Tasks:**
1. Learn about CI/CD concepts and benefits.
2. Explore GitHub Actions and its features.
3. Set up a basic CI/CD pipeline using GitHub Actions.
4. Integrate automated testing into the pipeline.
5. Deploy a simple application using the pipeline.

**References:**
- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [Getting Started with GitHub Actions](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions)

## Activity 4: CI/CD for Docker and Kubernetes with GitHub Actions
**Goal:** Implement CI/CD for containerized applications using GitHub Actions.
**Description:** Automate the build and deployment process for Docker and Kubernetes applications.

**Tasks:**
1. Create a GitHub Actions workflow to build and push Docker images.
2. Automate the deployment of Docker images to a Kubernetes cluster.
3. Implement automated testing for Docker and Kubernetes deployments.
4. Use Helm in the GitHub Actions workflow for Kubernetes deployments.
5. Set up notifications for build and deployment status.

**References:**
- [Docker and GitHub Actions](https://docs.github.com/en/actions/publishing-packages/publishing-docker-images)
- [Deploying to Kubernetes with GitHub Actions](https://docs.github.com/en/actions/deployment/deploying-to-your-cloud-provider/deploying-to-kubernetes)

## Activity 5: CI/CD for Terraform with GitHub Actions
**Goal:** Automate infrastructure deployment using Terraform and GitHub Actions.
**Description:** Integrate Terraform with a GitHub Actions pipeline.

**Tasks:**
1. Create a GitHub Actions workflow to manage Terraform configurations.
2. Automate the execution of `terraform plan` and `terraform apply`.
3. Implement automated testing for Terraform configurations.
4. Use environment-specific configurations with workspaces.
5. Set up notifications and monitoring for Terraform CI/CD pipelines.

**References:**
- [Terraform and GitHub Actions](https://www.terraform.io/docs/github-actions/index.html)
- [Using GitHub Actions with Terraform](https://learn.hashicorp.com/tutorials/terraform/github-actions)
