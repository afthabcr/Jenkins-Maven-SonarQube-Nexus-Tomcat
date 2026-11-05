# 🚀 End-to-End CI/CD Pipeline using Jenkins, Maven, SonarQube, Nexus & Tomcat

## 📌 Project Overview

This project demonstrates the implementation of an automated Continuous Integration and Continuous Deployment (CI/CD) pipeline using Jenkins.

The pipeline automates the process of building, testing, analyzing code quality, managing artifacts, and deploying a Java web application.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Jenkins | CI/CD Automation |
| Maven | Build Automation |
| SonarQube | Code Quality Analysis |
| Nexus Repository | Artifact Management |
| Apache Tomcat | Application Deployment |
| AWS EC2 | Cloud Infrastructure |
| Git & GitHub | Version Control |
| Ubuntu Linux | Server Administration |

## 🏗️ CI/CD Pipeline Architecture

```text
Developer
    |
    v
GitHub Repository
    |
    v
Jenkins Pipeline
    |
    v
Maven Build
    |
    v
SonarQube Analysis
    |
    v
Nexus Repository
    |
    v
Apache Tomcat
    |
    v
Deployed Web Application
```

## ⚙️ CI/CD Pipeline Flow
1. Developer pushes code to GitHub.
2. Jenkins clones the repository.
3. Maven builds the application and generates a WAR file.
4. SonarQube performs code quality analysis.
5. WAR artifact is uploaded to Nexus Repository.
6. Jenkins deploys the WAR file to Apache Tomcat using SCP over SSH.
7. The application is successfully deployed on the Tomcat server.


## 📂 Project Structure

Jenkins-Maven-SonarQube-Nexus-Tomcat/
│
├── Screenshots/
│
├── architeture/
│
├── src/
│   └── main/
│       └── webapp/
│
├── .gitignore
├── Jenkinsfile
├── pom.xml
├── LICENSE
└── README.md

---

## 🔑 Key Features

- Automated CI/CD pipeline using Jenkins.
- Maven-based Java application build.
- Static code analysis using SonarQube.
- Artifact storage using Nexus Repository Manager.
- Automated deployment using Apache Tomcat.
- Cloud infrastructure using AWS EC2.
- Source code management using Git and GitHub.

---

## 📚 Learning Outcomes

- Hands-on experience with Jenkins CI/CD pipelines.
- Understanding Maven build lifecycle.
- Integration of SonarQube with Jenkins.
- Artifact management using Nexus.
- Java application deployment using Apache Tomcat.
- AWS EC2 and Linux server administration.
- Practical understanding of DevOps automation.

---

## 👨‍💻 Author

Afthab CR

LinkedIn: www.linkedin.com/in/afthabcr/

GitHub: https://github.com/afthabcr/
