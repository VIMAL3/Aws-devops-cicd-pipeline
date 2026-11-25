# AWS DevOps & CI/CD Pipeline

Hands-on documentation and basic CI/CD workflow created for the **AWS DevOps & CI/CD** internship module.

## Key Objectives Covered
* **Git & GitHub Fundamentals:** Repository setup, commits, branches, and remote push/pull workflows.
* **Version Control:** Tracking code changes cleanly with commit history and rollback safety.
* **CI/CD Concepts:** Continuous Integration (automated checks/build on push) and Continuous Deployment (automated release to target environment).
* **AWS CI/CD Concepts:** Understanding AWS CodeCommit, CodeBuild, CodeDeploy, and CodePipeline alongside GitHub Actions.
* **Basic Deployment Pipeline:** Configured an automated workflow file (`.github/workflows/ci-cd-demo.yml`) triggered on `push` to `main`.
* **Workflow Documentation:** Documented end-to-end build, test, and deployment stages below.

## CI/CD Pipeline Workflow
`Developer (Git Push)` -> `GitHub Repository` -> `CI/CD Workflow (Build & Validate)` -> `Deployment Stage`

## Repository Files
* `index.html` — Sample application artifact validated during the pipeline run.
* `.github/workflows/ci-cd-demo.yml` — Automated CI/CD pipeline configuration.
