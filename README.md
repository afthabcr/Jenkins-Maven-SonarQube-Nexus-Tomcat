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

---


## ⚙️ CI/CD Pipeline Flow
1. Developer pushes code to GitHub.
2. Jenkins clones the repository.
3. Maven builds the application and generates a WAR file.
4. SonarQube performs code quality analysis.
5. WAR artifact is uploaded to Nexus Repository.
6. Jenkins deploys the WAR file to Apache Tomcat using SCP over SSH.
7. The application is successfully deployed on the Tomcat server.


## 📂 Project Structure

```
src/
Jenkinsfile
pom.xml
README.md
architecture/
screenshots/
```

---

## 🏗️ Architecture

https://github.com/ashinantony111/PROJECT--JENKINS-MAVEN-SONARQUBE-NEXUS-TOMCAT/tree/3e27dc8aa7403bc064d651cb794afb3fe20d93cd/architeture
---

## 📸 Project Screenshots

### Jenkins Pipeline
https://github.com/ashinantony111/PROJECT--JENKINS-MAVEN-SONARQUBE-NEXUS-TOMCAT/blob/b8b5bbedb72dce9e76a26d86b226ca79dd1879de/Screenshots/6.complete-pipeline-success.png

### SonarQube Analysis
https://github.com/ashinantony111/PROJECT--JENKINS-MAVEN-SONARQUBE-NEXUS-TOMCAT/blob/b8b5bbedb72dce9e76a26d86b226ca79dd1879de/Screenshots/3.sonarqube-analysis-success.png

### Nexus Repository Upload
https://github.com/ashinantony111/PROJECT--JENKINS-MAVEN-SONARQUBE-NEXUS-TOMCAT/blob/b8b5bbedb72dce9e76a26d86b226ca79dd1879de/Screenshots/4.nexus-artifact-upload.png

### Apache Tomcat Deployment
https://github.com/ashinantony111/PROJECT--JENKINS-MAVEN-SONARQUBE-NEXUS-TOMCAT/blob/b8b5bbedb72dce9e76a26d86b226ca79dd1879de/Screenshots/5.tomcat-deployment.png

---

## ✅ Features

- Automated CI/CD Pipeline
- Continuous Code Quality Analysis
- Artifact Version Management
- Automated Deployment
- End-to-End DevOps Workflow
- AWS EC2 Based Infrastructure

---

## 👨‍💻 Author

Ashin Antony

LinkedIn: www.linkedin.com/in/ashin-antony-7186b3389

GitHub: https://github.com/ashinantony111

