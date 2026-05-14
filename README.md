# Cloud-Native Professional Portfolio 🚀
### Hosted on Azure | Automated with GitHub Actions

This repository contains a professional web portfolio deployed on **Microsoft Azure** using **Static Web Apps**. This project demonstrates my ability to implement a full **CI/CD pipeline**, connecting source control with cloud infrastructure for automated deployments.

## 🌐 Live Demo
You can view the live site here: [https://zealous-mushroom-02a35510f.7.azurestaticapps.net](https://zealous-mushroom-02a35510f.7.azurestaticapps.net)

## 🛠️ Technical Stack
* **Cloud Provider:** Microsoft Azure
* **Hosting Service:** Azure Static Web Apps (Serverless)
* **CI/CD Tooling:** GitHub Actions
* **Language:** HTML5 / CSS3

## 🏗️ Architecture Features
* **Automated Deployment:** Every change pushed to the `main` branch triggers a GitHub Actions workflow that builds and deploys the site to Azure.
* **Global Distribution:** The site is hosted on Azure's global edge network, ensuring low latency and high availability.
* **Cloud Governance:** Configured within a dedicated **Azure Resource Group** (`RG_Oscar_Portfolio`) for organized lifecycle management.
* **Security:** Integrated with SSL/TLS encryption by default through Azure.

## ⚙️ How it Works
1.  **Code:** The source code is maintained in this GitHub repository.
2.  **Trigger:** A "Push" or "Pull Request" to the `main` branch activates the workflow defined in `.github/workflows/`.
3.  **Deploy:** Azure Static Web Apps engine synchronizes the content and updates the public URL in real-time.

## 👨‍💻 About the Author
I am a Cloud Enthusiast and IT Professional focused on **Azure** and **AWS** ecosystems. I specialize in cloud automation, infrastructure as code, and modern deployment strategies.

---
*This project was built as part of my professional development in Cloud Computing.*
