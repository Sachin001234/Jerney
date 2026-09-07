# 🛤️ Jerney — DevSecOps CI/CD Project

A blog platform application used as the base application for implementing a complete DevOps CI/CD workflow.

The application source code was taken from an existing project and my contribution focused on the **DevOps implementation, automation, code quality analysis, and deployment pipeline**.

![Tech Stack](https://img.shields.io/badge/Git-GitHub-F05032?style=flat-square&logo=git&logoColor=white)
![Tech Stack](https://img.shields.io/badge/Jenkins-CI%2FCD-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Tech Stack](https://img.shields.io/badge/SonarQube-Code%20Quality-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![Tech Stack](https://img.shields.io/badge/Docker-Containerization-2496ED?style=flat-square&logo=docker&logoColor=white)
![Tech Stack](https://img.shields.io/badge/AWS-EC2-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Tech Stack](https://img.shields.io/badge/Linux-Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)

---

## 🎯 Project Objective

The objective of this project was to take an existing web application and build a **DevOps workflow around it**.

The implementation focuses on:

- Source code management using GitHub
- Automated CI/CD using Jenkins
- GitHub webhook integration
- Automated code quality analysis using SonarQube
- SonarQube Quality Gate integration
- Docker image build automation
- Deployment to AWS EC2
- Linux server administration
- Application verification after deployment

The application itself was used as the workload for demonstrating the DevOps workflow.

---

## 🏗️ DevOps Architecture

```text
                    ┌─────────────────┐
                    │     GitHub      │
                    │   Source Code   │
                    └────────┬────────┘
                             │
                             │ Webhook
                             ▼
                    ┌─────────────────┐
                    │     Jenkins     │
                    │     CI/CD       │
                    └────────┬────────┘
                             │
                 ┌───────────┴───────────┐
                 │                       │
                 ▼                       ▼
        ┌─────────────────┐     ┌─────────────────┐
        │    SonarQube    │     │     Docker      │
        │  Code Analysis  │     │  Image Build    │
        └────────┬────────┘     └────────┬────────┘
                 │                       │
                 │ Quality Gate           │
                 └───────────┬───────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │     AWS EC2     │
                    │   Deployment    │
                    └────────┬────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │   Running App   │
                    └─────────────────┘
```

---

## 🔧 Technologies & Tools

| Technology | Purpose |
|------------|---------|
| Git & GitHub | Source code management |
| GitHub Webhooks | Trigger Jenkins pipeline automatically |
| Jenkins | CI/CD automation |
| SonarQube | Static code analysis |
| SonarQube Quality Gate | Code quality validation |
| Docker | Application containerization |
| AWS EC2 | Cloud infrastructure and deployment |
| Elastic IP | Stable public IP for EC2 services |
| Ubuntu Linux | Server operating system |
| Bash | Server and deployment commands |

---

# 🛤️ Jerney — DevSecOps CI/CD Project

A blog platform application used as the base application for implementing a complete DevOps CI/CD workflow.

The application source code was taken from an existing project and my contribution focused on the **DevOps implementation, automation, code quality analysis, and deployment pipeline**.

![Tech Stack](https://img.shields.io/badge/Git-GitHub-F05032?style=flat-square&logo=git&logoColor=white)
![Tech Stack](https://img.shields.io/badge/Jenkins-CI%2FCD-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Tech Stack](https://img.shields.io/badge/SonarQube-Code%20Quality-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![Tech Stack](https://img.shields.io/badge/Docker-Containerization-2496ED?style=flat-square&logo=docker&logoColor=white)
![Tech Stack](https://img.shields.io/badge/AWS-EC2-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Tech Stack](https://img.shields.io/badge/Linux-Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)

---

## 🎯 Project Objective

The objective of this project was to take an existing web application and build a **DevOps workflow around it**.

The implementation focuses on:

- Source code management using GitHub
- Automated CI/CD using Jenkins
- GitHub webhook integration
- Automated code quality analysis using SonarQube
- SonarQube Quality Gate integration
- Docker image build automation
- Deployment to AWS EC2
- Linux server administration
- Application verification after deployment

The application itself was used as the workload for demonstrating the DevOps workflow.

---

## 🏗️ DevOps Architecture

```text
                    ┌─────────────────┐
                    │     GitHub      │
                    │   Source Code   │
                    └────────┬────────┘
                             │
                             │ Webhook
                             ▼
                    ┌─────────────────┐
                    │     Jenkins     │
                    │     CI/CD       │
                    └────────┬────────┘
                             │
                 ┌───────────┴───────────┐
                 │                       │
                 ▼                       ▼
        ┌─────────────────┐     ┌─────────────────┐
        │    SonarQube    │     │     Docker      │
        │  Code Analysis  │     │  Image Build    │
        └────────┬────────┘     └────────┬────────┘
                 │                       │
                 │ Quality Gate           │
                 └───────────┬───────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │     AWS EC2     │
                    │   Deployment    │
                    └────────┬────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │   Running App   │
                    └─────────────────┘
```

---

## 🔧 Technologies & Tools

| Technology | Purpose |
|------------|---------|
| Git & GitHub | Source code management |
| GitHub Webhooks | Trigger Jenkins pipeline automatically |
| Jenkins | CI/CD automation |
| SonarQube | Static code analysis |
| SonarQube Quality Gate | Code quality validation |
| Docker | Application containerization |
| AWS EC2 | Cloud infrastructure and deployment |
| Elastic IP | Stable public IP for EC2 services |
| Ubuntu Linux | Server operating system |
| Bash | Server and deployment commands |

---

# 🛤️ Jerney — DevSecOps CI/CD Project

A blog platform application used as the base application for implementing a complete DevOps CI/CD workflow.

The application source code was taken from an existing project and my contribution focused on the **DevOps implementation, automation, code quality analysis, and deployment pipeline**.

![Tech Stack](https://img.shields.io/badge/Git-GitHub-F05032?style=flat-square&logo=git&logoColor=white)
![Tech Stack](https://img.shields.io/badge/Jenkins-CI%2FCD-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Tech Stack](https://img.shields.io/badge/SonarQube-Code%20Quality-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![Tech Stack](https://img.shields.io/badge/Docker-Containerization-2496ED?style=flat-square&logo=docker&logoColor=white)
![Tech Stack](https://img.shields.io/badge/AWS-EC2-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Tech Stack](https://img.shields.io/badge/Linux-Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)

---

## 🎯 Project Objective

The objective of this project was to take an existing web application and build a **DevOps workflow around it**.

The implementation focuses on:

- Source code management using GitHub
- Automated CI/CD using Jenkins
- GitHub webhook integration
- Automated code quality analysis using SonarQube
- SonarQube Quality Gate integration
- Docker image build automation
- Deployment to AWS EC2
- Linux server administration
- Application verification after deployment

The application itself was used as the workload for demonstrating the DevOps workflow.

---

## 🏗️ DevOps Architecture

```text
                    ┌─────────────────┐
                    │     GitHub      │
                    │   Source Code   │
                    └────────┬────────┘
                             │
                             │ Webhook
                             ▼
                    ┌─────────────────┐
                    │     Jenkins     │
                    │     CI/CD       │
                    └────────┬────────┘
                             │
                 ┌───────────┴───────────┐
                 │                       │
                 ▼                       ▼
        ┌─────────────────┐     ┌─────────────────┐
        │    SonarQube    │     │     Docker      │
        │  Code Analysis  │     │  Image Build    │
        └────────┬────────┘     └────────┬────────┘
                 │                       │
                 │ Quality Gate           │
                 └───────────┬───────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │     AWS EC2     │
                    │   Deployment    │
                    └────────┬────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │   Running App   │
                    └─────────────────┘
```

---

## 🔧 Technologies & Tools

| Technology | Purpose |
|------------|---------|
| Git & GitHub | Source code management |
| GitHub Webhooks | Trigger Jenkins pipeline automatically |
| Jenkins | CI/CD automation |
| SonarQube | Static code analysis |
| SonarQube Quality Gate | Code quality validation |
| Docker | Application containerization |
| AWS EC2 | Cloud infrastructure and deployment |
| Elastic IP | Stable public IP for EC2 services |
| Ubuntu Linux | Server operating system |
| Bash | Server and deployment commands |

---

## 🔄 CI/CD Pipeline

The project uses Jenkins to automate the application delivery workflow.

```text
Developer
    │
    ▼
GitHub Repository
    │
    │
    ▼
GitHub Webhook
    │
    ▼
  Jenkins
    │
    ├── Checkout Source Code
    │
    ├── SonarQube Analysis
    │
    ├── Quality Gate
    │
    ├── Build Docker Images
    │
    ├── Deploy
    │
    └── Verify Deployment
    │
    ▼
 Running Application
```

### Pipeline Stages

1. **Checkout SCM**
   - Retrieves the source code from GitHub.

2. **Checkout**
   - Prepares the required source code for the pipeline execution.

3. **Create Environment**
   - Prepares the environment required for the pipeline.

4. **SonarQube Analysis**
   - Performs automated static code analysis.
   - Sends the analysis results to the SonarQube server.

5. **Quality Gate**
   - Waits for the SonarQube analysis to complete.
   - Checks the SonarQube Quality Gate result.
   - Prevents the pipeline from continuing when the quality gate fails.

6. **Build Docker Images**
   - Builds Docker images for the application.

7. **Deploy**
   - Deploys the application to the configured AWS environment.

8. **Verify Deployment**
   - Performs a deployment verification after the application is deployed.

---

## 🔗 GitHub Webhook Integration

A GitHub webhook is configured to automatically notify Jenkins when changes are pushed to the repository.

```text
Git Push
   │
   ▼
GitHub Repository
   │
   │ HTTP POST Webhook
   ▼
Jenkins
   │
   ▼
CI/CD Pipeline
```

This removes the need to manually start the Jenkins job after every code push.

---

## ☁️ AWS EC2 Deployment

The DevOps pipeline was configured to deploy the application on an **AWS EC2 instance running Ubuntu Linux**.

### Deployment Environment

- **Cloud:** AWS
- **Compute:** Amazon EC2
- **Operating System:** Ubuntu Linux
- **Containerization:** Docker
- **CI/CD:** Jenkins
- **Code Quality:** SonarQube

### Deployment Workflow

```text
GitHub
   │
   ▼
Jenkins
   │
   ├── Checkout Source Code
   ├── SonarQube Analysis
   ├── Quality Gate
   ├── Build Docker Images
   ├── Deploy
   └── Verify Deployment
   │
   ▼
AWS EC2
   │
   └── Running Application

## ☁️ AWS Infrastructure

AWS EC2 was used to host the DevOps environment and application deployment.

The project uses separate EC2 instances for the required DevOps services.

```text
                    AWS
                     │
          ┌──────────┴──────────┐
          │                     │
       Jenkins              SonarQube
       EC2 Instance         EC2 Instance
          │                     │
          │                     │
          └──────────┬──────────┘
                     │
                     ▼
                Application
                EC2 Instance
                     │
                Elastic IP
                     │
                     ▼
              Public Access
```

### AWS Components

- **EC2** — Hosts Jenkins, SonarQube, and the application environment.
- **Elastic IP** — Provides a stable public IP address for the application/Jenkins environment.
- **Security Groups** — Control inbound and outbound network access to the EC2 instances.
- **Ubuntu Linux** — Used as the operating system for the EC2 servers.

### Network Ports Used

| Service | Port | Purpose |
|---------|------|---------|
| SSH | 22 | Server administration |
| HTTP | 80 | Web application access |
| Jenkins | 8080 | Jenkins web interface |
| SonarQube | 9000 | SonarQube web interface |
| Backend | 5000 | Application backend |
| PostgreSQL | 5432 | Database communication |

---

## 🐳 Docker

Docker was used to package the application into containers as part of the CI/CD workflow.

The Jenkins pipeline automatically builds the required Docker images during the pipeline execution.

```text
Source Code
     │
     ▼
  Jenkins
     │
     ▼
Docker Build
     │
     ▼
Docker Images
     │
     ▼
Deployment
```

Docker provides a consistent application environment and reduces differences between development and deployment environments.

---

## ⚙️ Jenkins CI/CD

Jenkins was used to automate the CI/CD workflow for the application.

### Jenkins Implementation

- Configured a Jenkins pipeline for automated application delivery.
- Connected Jenkins with the GitHub repository.
- Configured GitHub Webhook integration to trigger builds automatically.
- Integrated SonarQube for automated code quality analysis.
- Configured the SonarQube Quality Gate to control pipeline execution.
- Added Docker image build automation.
- Added deployment and deployment verification stages.

### Pipeline Stages

```text
Checkout SCM
     ↓
Checkout
     ↓
Create Environment
     ↓
SonarQube Analysis
     ↓
Quality Gate
     ↓
Build Docker Images
     ↓
Deploy
     ↓
Verify Deployment

---

## 🔍 SonarQube Code Quality

SonarQube was integrated into the Jenkins pipeline to perform automated code quality analysis.

```text
Jenkins
   │
   ▼
SonarQube Analysis
   │
   ▼
Quality Gate
   │
   ├── PASS ──▶ Continue Pipeline
   │
   └── FAIL ──▶ Stop Pipeline
```

The Jenkins pipeline waits for the SonarQube analysis to complete and then evaluates the Quality Gate status before continuing with later deployment stages.

---

## 🛠️ DevOps Implementation

The following DevOps components were implemented as part of this project:

- 🔗 **Git & GitHub**
  - Managed the project source code using Git.
  - Used Git branches and commits for version control.

- ⚙️ **Jenkins CI/CD**
  - Created and configured a Jenkins pipeline.
  - Automated the application build and deployment workflow.
  - Configured pipeline stages for source checkout, analysis, quality validation, Docker build, deployment, and verification.

- 🪝 **GitHub Webhooks**
  - Integrated GitHub with Jenkins using webhooks.
  - Configured automatic pipeline triggering whenever changes are pushed to the repository.

- 🔍 **SonarQube**
  - Integrated SonarQube with Jenkins.
  - Added automated static code analysis to the CI/CD pipeline.
  - Configured the SonarQube Quality Gate.

- 🐳 **Docker**
  - Integrated Docker image building into the Jenkins pipeline.
  - Automated Docker image creation as part of the CI/CD process.

- ☁️ **AWS EC2**
  - Provisioned and configured EC2 instances for the DevOps environment.
  - Configured required services and networking for Jenkins, SonarQube, and application deployment.

- 🌐 **Elastic IP**
  - Associated an Elastic IP with the EC2 environment.
  - Used the stable public IP for services that require consistent external access.

- 🐧 **Linux / Ubuntu**
  - Managed Ubuntu-based EC2 servers through SSH.
  - Installed and configured required DevOps tools and services.
  - Used Linux commands for server administration and troubleshooting.

- 🔐 **Security Groups**
  - Configured AWS Security Group rules for required service ports.
  - Controlled access to SSH, HTTP, Jenkins, and SonarQube services.

---

## 📊 Pipeline Result

The completed CI/CD workflow provides an automated path from source code changes to deployment:

```text
GitHub Push
     │
     ▼
GitHub Webhook
     │
     ▼
Jenkins Pipeline
     │
     ├── Checkout
     │
     ├── SonarQube Analysis
     │
     ├── Quality Gate
     │
     ├── Docker Build
     │
     ├── Deployment
     │
     └── Deployment Verification
     │
     ▼
Application Running on AWS
```

The pipeline can be triggered automatically through the GitHub webhook, reducing manual intervention during application delivery.

---

## 👨‍💻 My Contribution

The application was used as the workload for this project, while my primary focus was on the **DevOps implementation and deployment workflow**.

I implemented and configured:

- GitHub repository and source-code workflow
- Jenkins CI/CD pipeline
- GitHub → Jenkins webhook integration
- SonarQube integration with Jenkins
- Automated SonarQube code analysis
- SonarQube Quality Gate validation
- Docker image build automation
- AWS EC2 deployment environment
- Elastic IP configuration
- Linux/Ubuntu server administration
- AWS Security Group configuration
- Deployment verification

The project demonstrates how an existing application can be integrated into an automated **CI/CD and DevSecOps workflow**.

---

## 🎓 Skills Demonstrated

### Source Control
- Git
- GitHub
- Git branching and commits
- Repository management
- GitHub webhook integration

### CI/CD
- Jenkins
- Jenkins Pipeline
- Automated builds
- Automated deployment
- Pipeline stage management

### Code Quality
- SonarQube
- Static code analysis
- Quality Gates
- Jenkins-SonarQube integration

### Containerization
- Docker
- Docker image building
- Container-based application deployment

### Cloud & Infrastructure
- AWS EC2
- Elastic IP
- Security Groups
- Linux/Ubuntu server administration

### Automation & Troubleshooting
- Bash/Linux commands
- SSH
- CI/CD troubleshooting
- Webhook troubleshooting
- Service and network configuration

### DevOps

- CI/CD automation
- DevSecOps workflow
- Automated code quality checks
- Containerized application deployment
- Infrastructure and deployment troubleshooting
---

## 🚀 Project Outcome

This project demonstrates a practical DevOps workflow in which source-code changes can automatically trigger a Jenkins pipeline, undergo SonarQube code-quality analysis, pass through a Quality Gate, build Docker images, and proceed toward deployment on AWS EC2.

The project provided hands-on experience with integrating multiple DevOps tools into a single automated workflow rather than working with each tool independently.

---

## 📌 Resume Description

**Jerney — DevOps CI/CD Pipeline**

- Implemented a Jenkins-based CI/CD pipeline for an existing web application with automated source checkout, SonarQube analysis, Quality Gate validation, Docker image building, deployment, and verification.
- Integrated GitHub Webhooks with Jenkins to automatically trigger pipeline execution on code changes.
- Deployed and configured DevOps services on AWS EC2 using Ubuntu Linux, Security Groups, and Elastic IP.
- Integrated SonarQube with Jenkins for automated static code analysis and quality validation.

---

## 🔑 Key Technologies

**Git | GitHub | GitHub Webhooks | Jenkins | Jenkins Pipeline | SonarQube | Docker | AWS EC2 | Elastic IP | Linux | Ubuntu | Bash**

---

## 📁 Project Structure

```text
Jerney/
├── frontend/          # Existing React frontend
├── backend/           # Existing Node.js backend
├── deploy/            # Deployment-related files
├── Jenkinsfile        # Jenkins CI/CD pipeline
└── README.md          # Project documentation
```

---

## ⚠️ Project Scope

This project focuses on the **DevOps engineering and deployment workflow** rather than application development.

The application source code was used as an existing workload so that the project could focus on implementing CI/CD, code-quality automation, containerization, AWS deployment, and Linux server administration.

---

## 🏁 Conclusion

Jerney served as my first practical DevOps project, allowing me to work with a complete CI/CD workflow using GitHub, Jenkins, SonarQube, Docker, and AWS EC2.

The project establishes the foundation for my upcoming DevOps projects, where I will expand into infrastructure as code, Kubernetes, configuration management, and GitOps.

---

Built with ⚙️ DevOps tools and a lot of terminal troubleshooting. 🚀
