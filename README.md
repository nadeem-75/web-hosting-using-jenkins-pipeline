# WebPage Hosting Using Jenkins Pipeline

This project demonstrates how to set up automated web page hosting using Jenkins Pipeline. The implementation showcases continuous integration and deployment (CI/CD) for static web content.

## Project Overview

The project uses Jenkins to automatically build and deploy a static webpage. When changes are pushed to the repository, Jenkins automatically picks up the changes and deploys the updated webpage.

## Prerequisites

- Jenkins (version 2.485 or higher)
- Git
- Web server (Apache/Nginx)
- Jenkins Plugins:
  - Pipeline
  - Git
  - Credentials

## Jenkins Configuration

### System Requirements
- Jenkins URL: http://54.167.91.115:8080/
- Recommended: Set up distributed builds for better security

### Initial Setup
1. Install required plugins
2. Configure system settings
3. Set up build agents (recommended)
4. Configure credentials

## Pipeline Structure

The pipeline is configured to:
1. Clone the repository
2. Validate HTML content
3. Deploy to web server
4. Verify deployment

![jenkins6](https://github.com/user-attachments/assets/da815838-15fa-43ce-b252-7670fb379bd3)


## Repository Structure

```
web-hosting-using-jenkins-pipeline/
├── Jenkinsfile
├── src/
│   └── *.html
├── styles/
│   └── *.css
└── README.md
```

## Security Considerations

- Use Jenkins security features
- Configure proper access controls
- Follow the principle of least privilege
- Use credential management for sensitive data
- Set up distributed builds instead of using built-in node

## Quick Start

1. Fork this repository
2. Set up Jenkins using the provided configuration
3. Create a new Pipeline job in Jenkins
4. Point the Pipeline to your repository
5. Run the build

## Viewing the Result


After successful deployment, your webpage will be accessible at:
```
http://[your-server-ip]/web-hosting-using-jenkins-pipeline/[page].html
```

Example: http://3.90.62.178/web-hosting-using-jenkins-pipeline/nadeem.html


![final ](https://github.com/user-attachments/assets/ef5ecc43-dacd-4776-9d52-e66b6f3bcf8c)

## Author

Shaik Nadeem

