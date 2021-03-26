# Provision an EKS Cluster on AWS using Terraform

Today more than ever, networks need to be agile. Cisco and DevNet can help you prepare your infrastructure for whatever comes next.
Let’s take a look at how automation can quickly and efficiently enable your business to adjust to changing IT demands. 
One IT vertical that’s required major innovation and adaptability in order to respond to the pandemic fallout is higher education. 
The oscillation between on-site, partially remote, and fully-remote education has created a particularly challenging scenario for colleges and universities.



![app](assets/devnet.gif)


## What is Terraform?
Terraform is a tool for building, changing, and versioning infrastructure safely and efficiently. Terraform can manage existing and popular service providers as well as custom in-house solutions.

### The key feature of Terraform is Infrastructure as Code
Infrastructure as Code (IaC) allows you to provision and manage the full technology stack using automation, by translating manual, repetitive tasks into reusable, robust, secure, and distributable code. Using IaC, you can create golden templates to simplify your work. You can continuously design-build-deploy-destroy-rollback in live environments so your network can stay agile. And you can use APIs to innovate. 
## Requirements

1. Clone the Terraform plan in this Repo
2. Install and configure [Terraform locally](https://learn.hashicorp.com/tutorials/terraform/install-cli) or have access to [Terraform Cloud](https://www.hashicorp.com/products/terraform)
3. An AWS account and [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html) installed


## Getting Started
1. Make sure you are in the code folder - `cd tf-aws-eks-cluster`
2. Initialize the directory - `terraform init`
3. Format and validate the configuration - `terraform fmt` and `terraform validate`
4. Create infrastructure - `terraform apply` 

To inspect the state of your infrastructure - `terraform show`

## SUCCESS
You have successfully stood up and entire Kubernetes cluster (EKS) in AWS. 
You are now ready to deploy your application containers.
Check out how to deploy the same infrastructure using [Cisco Intersight and Terraform onprem here](https://github.com/prathjan/iks-intersight-terraform)