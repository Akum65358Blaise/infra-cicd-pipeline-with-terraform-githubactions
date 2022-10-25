# Automation of Infrastructure using Github Actions and Terraform.


I am a big fan of popular CI/CD solutions such as Jenkins, GitHub Actions, Gitlab CI.

GitHub is well known for storing code and providing VCS over them, but it completely captured the market of automation with GitHub entering the CI-CD market using Github actions.

GitHub Actions is a continuous integration and continuous delivery (CI/CD) platform that allows you to automate your build, test, and deployment pipeline. You can create workflows that build and test every pull request to your repository, or deploy merged pull requests to production.

Terraform is a tool for provisioning infrastructure (or managing Infrastructure as Code). It supports almost all the cloud providers like AWS, Google Cloud, Azure, etc. Seamless integration of Terraform cloud with Terraform allows you to use Terraform to integrate with various CI-CD tools.

In this project, i automated the process of provisioning cloud infrastructure using github actions workflows and terraform. 

I created a CI/CD pipeline( Github actions workflow) that automatically build test and deploy infrastructure provisioned using terraform.

A practical use case of this project is in the company where they are two or more DevOps Engineers and one of them may not have access to the AWS console to provision or manage infrastructure. All he needs to do is to define the infrastructure in the terraform file, and push the changes to the branch of the repository which has Github actions repository secrets setup there. the actions will be triggered whenever a new push is made to the main branch and on any pull request. The pipeline runs and deploys the infrastructure.

