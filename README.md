<h1 align="center">SCA CS Project files</h1>
<h3>This repository contains terraform files used in provisioning Infrastructure on GCP for the <a href="https://github.com/Goodiec/SCA-CS-project">SCA CS project</a></h3>

<!-- TABLE OF CONTENTS -->

## Table of Contents

## Provisioning Kubernetes cluster on GCP
You have to have Terraform installed on your local computer to run Terraform commands and to provision on Google Cloud Platform (GCP), you have to you have to have a GCP account. 

To be able to provision these on GCP, you would need to create a project and enable the required APIs on Google Cloud Platform - Enable the compute engine API, the Kubernetes API, service management API & cloud resource manager API. They are easy to enable with just a click on GCP.

To get started, on your command line console, run 
```
terraform init
```
![t1](https://user-images.githubusercontent.com/15726413/115900702-292fae00-a458-11eb-8eef-5eea3b76edb6.PNG)

```
terraform plan
```
![t2](https://user-images.githubusercontent.com/15726413/115900701-292fae00-a458-11eb-81fa-0be667b98f79.PNG)

```
terraform apply
```
![t3](https://user-images.githubusercontent.com/15726413/115900694-2765ea80-a458-11eb-80c8-b851e36a7bc6.PNG)

What you see in the images are the expected outputs. If these run successfully, you should see the Kubernetes cluster in your GCP account.

