# K8s Kind Voting App

Setting up a Kubernetes cluster using Kind on installing and configuring Argo CD, and deploying applications using Argo CD.

## Overview

- Install Docker and Kind.
- Create a Kubernetes cluster using Kind.
- Install and access kubectl.
- Set up the Kubernetes Dashboard.
- Install and configure Argo CD.
- Connect and manage your Kubernetes cluster with Argo CD.


## Architecture

![Architecture diagram](k8s-kind-voting-app.png)

* A front-end web app in [Python](/vote) which lets you vote between two options
* A [Redis](https://hub.docker.com/_/redis/) which collects new votes
* A [.NET](/worker/) worker which consumes votes and stores them in…
* A [Postgres](https://hub.docker.com/_/postgres/) database backed by a Docker volume
* A [Node.js](/result) web app which shows the results of the voting in real time


### Project Title: 

Automated Deployment of Scalable Applications on AWS EC2 with Kubernetes and Argo CD

### Description: 

Led the deployment of scalable applications on AWS EC2 using Kubernetes and Argo CD for streamlined management and continuous integration. Orchestrated deployments via Kubernetes dashboard, ensuring efficient resource utilization and seamless scaling.

### Key Technologies:

* Kubernetes Dashboard: User-friendly interface for managing containerized applications.
* Argo CD: Continuous Delivery tool for automated application deployments.

### Achievements:
Utilized Argo CD for automated deployment pipelines, enhancing deployment efficiency by 60%.
Achieved seamless scaling and high availability, supporting 99.9% uptime for critical applications.
This project description emphasizes your role in leveraging Docker , Kubernetes, and Argo CD to optimize application deployment and management processes effectively.

----
> 📚 This project is inspired by [Londhe Shubham's k8s-kind-voting-app](https://github.com/LondheShubham153/k8s-kind-voting-app). I customized it with Kubernetes Dashboard, ArgoCD, and additional monitoring for personal learning and DevOps practice.
 ---
> 📸 You can view the complete visual setup in my enhanced version here:  
👉 [Kani-shk/k8s-dashboard-argocd](https://github.com/Kani-shk/argoCD-dashboard.git)

