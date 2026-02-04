# GitHub Actions: The Complete Guide (Coursework)

This repository contains my code, exercises, and projects developed while completing the [GitHub Actions - The Complete Guide](https://www.udemy.com/course/github-actions-the-complete-guide/) course on Udemy. 

The projects demonstrate a progression from basic CI/CD concepts to advanced workflow automation, custom actions, and security practices.

## 📚 Repository Structure

The repository is organized by course modules, with each folder containing the relevant starting code or completed exercises for that section:

| Module | Description | Key Concepts |
| :--- | :--- | :--- |
| **02. Git and Github Crash Course** | Basic refresher project. | Git basics, remote repositories. |
| **03. Basic Building Blocks** | Introduction to Actions syntax. | Workflows, Jobs, Steps, `runs-on`. |
| **04. Workflows and Events** | Deep dive into triggers. | `on` events, filters, activity types. |
| **05. Job Artifacts and Outputs** | Data sharing strategies. | Uploading/downloading artifacts, job outputs. |
| **06. Environment Variables & Secrets** | Configuration management. | GitHub Secrets, Environment Variables, Contexts. |
| **07. Controlling Execution** | Logic and flow control. | `if` conditions, Matrix strategies, reusable workflows. |
| **08. Jobs and Docker Containers** | Containerization in CI. | Running jobs in containers, service containers. |
| **09. Custom Actions** | Building reusable actions. | JavaScript Actions, Docker Actions, Composite Actions. |
| **10. Security and Permissions** | Securing pipelines. | `GITHUB_TOKEN` permissions, OIDC. |

## 🚀 Projects & Workflows

Each directory contains a `.github/workflows` folder defining the pipelines for that specific module. 

### Key Examples Included:
* **Deploy Website**: A recurrent project showing how to build and deploy a static site (using a Vue/Vite app).
* **Custom JavaScript Action**: A custom action located in Module 09 (`deploy-s3-javascript`) that automates deployment tasks.
* **Custom Docker Action**: A Python-based custom action located in Module 09 (`deploy-s3-docker`) demonstrating containerized logic.
* **Matrix Testing**: Workflows that run tests across multiple Node.js versions simultaneously.

> **Note**: Some workflows (specifically in Modules 6, 9, and 10) require specific **GitHub Secrets** (e.g., AWS credentials, Docker Hub tokens) to run successfully.

## 🛠 Technologies Used

* **CI/CD**: GitHub Actions (YAML)
* **Languages**: JavaScript (Node.js), Python
* **Tools**: Docker, Vite
* **Cloud Concepts**: AWS S3 Deployment (simulated or configured via OIDC)

## 🔗 Course Information

* **Course**: [GitHub Actions - The Complete Guide](https://www.udemy.com/course/github-actions-the-complete-guide/)
* **Platform**: Udemy

---
*This repository is for educational purposes and tracks my personal progress through the curriculum.*
