Here is your **edited and polished README file**, including the **proper code block** for your command:

---

# Deploy Your Website on Cloud Run on GCP

Deploy your website on **Cloud Run** using **Google Cloud Platform (GCP)**.

Cloud Run allows you to deploy applications using a fully managed serverless platform. You can use Cloud Run directly or deploy containers on Google Kubernetes Engine (GKE).
In this lab, you’ll follow the Cloud Run path.

## 📘 What You Will Do

The steps mirror a real cloud developer’s workflow:

1. Create a Docker container from your application.
2. Deploy the container to Cloud Run.
3. Modify the webpage.
4. Deploy a new version with zero downtime.

---

## 🎯 What You Will Learn

This lab teaches you how to:

* Use **Cloud Build** to create a Docker image and upload it to **Artifact Registry**.
* Deploy Docker images to **Cloud Run**.
* Manage Cloud Run services.
* Configure an application's endpoint on Cloud Run.

---

## © Credit

**No copyright intended.**
All rights and credits for the original content belong to **Google Cloud** (Google Cloud Skills Boost).
DM for credit or removal requests. 🙏

---

## ▶️ Run the following command in Cloud Shell:

```bash
curl -LO https://raw.githubusercontent.com/dev23-extremis/Deploy-Your-Website-on-Cloud-Run-on-GCP/main/devang.sh
sudo chmod +x devang.sh
./devang.sh
```
