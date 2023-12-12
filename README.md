# Executed EKS cluster deployment using Terraform within Jenkins, optimizing Kubernetes CI/CD workflows.

![workflow](https://github.com/pranavp14/tf-jenkins-eks/assets/86883246/fe958428-fb25-4264-8722-c3cae6b541b4)

EKS Cluster: Amazon Elastic Kubernetes Service (EKS) is a managed Kubernetes service that Amazon Web Services (AWS) offers. It simplifies the process of deploying, managing, and scaling containerized applications using Kubernetes on AWS infrastructure.

Terraform: Terraform is an infrastructure as code (IaC) tool that allows you to define and provision infrastructure resources in a declarative way. In this context, it's likely used to script the deployment of the EKS cluster, specifying the desired state of the infrastructure.

Jenkins: Jenkins is an automation server often used for continuous integration and continuous deployment (CI/CD). It helps automate building, testing, and deploying applications.

Kubernetes CI/CD workflows: This refers to the processes and pipelines established within Kubernetes for continuous integration and deployment. CI/CD workflows automate the building, testing, and deployment of applications in a Kubernetes environment.

 
## Introduction 
 This project provides a comprehensive guide and a set of resources to  EKS cluster deployment using Terraform within Jenkins, optimizing Kubernetes CI/CD workflows.Terraform is an open-source infrastructure as code (IaC) tool that allows you to define and provision infrastructure using a declarative configuration language. 

## Steps Performed:
 - Create an EC2 Instance + Jenkins
 - Write tf code for EKS cluster.
 - Push Code on Github account.
 - Create a Jenkins pipeline for EKS cluster deployment.
 - Deploy the changes on AWS
 - Implement a deployment file through kubectl and
 - Access Nginx application with help of a particular load balancer 
 
## Screenshots : 

![Jenkins-terraform-creation](https://github.com/pranavp14/tf-jenkins-eks/assets/86883246/5d0b5cc4-accc-4e15-ba68-a78576fe085d)
![jen-credentials](https://github.com/pranavp14/tf-jenkins-eks/assets/86883246/e2440865-3e5e-425c-a134-1450cd54a086)
![action](https://github.com/pranavp14/tf-jenkins-eks/assets/86883246/6c54dd02-33d0-4b6d-b13e-aa4b9efd6f21)
![complete-workflow-jenkins jpg](https://github.com/pranavp14/tf-jenkins-eks/assets/86883246/519bdf0d-96c1-4176-993c-e1db4f355c8c)
![nginx-running-aws](https://github.com/pranavp14/tf-jenkins-eks/assets/86883246/89312d2c-39d5-46ac-aa8d-6dabf4442916)










