### Complete CI/CD with Terraform

### Technologies Used:

Terraform, Jenkins, Docker, AWS, Git, Java, Maven, Linux, Docker Hub

### Project Description

Integrate provisioning stage into complete CI/CD Pipeline to automate provisioning server instead of deploying to an existing server

1- Create SSH Key Pair

2- Install Terraform inside Jenkins container

3- Add Terraform configuration to application’s git repository

4- Adjust Jenkinsfile to add “provision” step to the CI/CD pipeline that provisions EC2 instance So the complete CI/CD project we build has the following configuration:

a. CI step: Build artifact for Java Maven application

b. CI step: Build and push Docker image to Docker Hub

c. CD step: Automatically provision EC2 instance using TF

d. CD step: Deploy new application version on the provisioned EC2 instance with Docker Compose
