# Deploy-Your-Website-on-Cloud-Run-on-GCP
Deploy Your Website on Cloud Run on Goggle Cloud Platform

You can use Cloud Run's fully managed PaaS solution or your own Google Kubernetes Engine (GKE) clusters to implement "serverless" development in containers.  In this lab, you will run the latter situation.

 The exercises are arranged to mirror the typical experience of a cloud developer:


 From your application, create a Docker container.
 Install the container on Cloud Run.
 Change the webpage
 Release a new version with no downtime.
 What you'll discover
 This lab will teach you how to:

 Use Cloud Build to create a Docker image, then upload it to the Artifact Registry.
 Install Docker images on Cloud Run
 Oversee Cloud Run installations
 Configure an application's endpoint on Cloud Run

©Credit
DM for credit or removal request (no copyright intended) ©All rights and credits for the original content belong to Google Cloud Google Cloud Skill Boost website 🙏

 Run the following command in the cloud shell:
 curl -LO https://raw.githubusercontent.com/dev23-extremis/Deploy-Your-Website-on-Cloud-Run-on-GCP/main/devang.sh
sudo chmod +x devang.sh
./devang.sh
