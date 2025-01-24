
# 🏦 Fintech-LSI

<div align="center"><img width="200" alt="Screenshot 2025-01-24 at 23 00 51" src="https://github.com/user-attachments/assets/90bd6329-f10c-4541-a430-338e1ec0c99e" /></div>


Welcome to Fintech-LSI, a comprehensive financial technology platform that provides advanced tools and services for financial analysis, risk assessment, and market predictions.

## 🌟 Overview

Fintech-LSI is an organization dedicated to building robust, scalable financial technology solutions. Our platform combines modern web technologies with sophisticated machine learning models to deliver reliable financial services.

## 🏗 Project Structure

Our platform consists of several key components:

- **fintech-infrastructure**: Core infrastructure components for our fintech ecosystem
- **fintech-monitoring**: Centralized monitoring stack leveraging Grafana & Prometheus for reliability tracking
- **fintech-credit-risk-prediction**: ML model for credit risk assessment using borrower information
- **fintech-market-prediction**: Market prediction and analysis tools
- **fintech-web-client**: Modern Angular-based web application for financial services management
- **Config-server**: Spring Cloud Config Server for centralized configuration management

## 💻 Technologies

Our tech stack includes:

- **Frontend**: TypeScript, Angular
- **Backend**: SpringBoot, Spring Cloud
- **Data Science**: Jupyter Notebook, Flask
- **DevOps**: Jenkins, Docker, Kubernetes
- **Monitoring**: Grafana, Prometheus

## 🚀 Getting Started

1. Clone the desired repository
2. Follow the specific setup instructions in each repository's README
3. For development environment setup, ensure you have:
   - Java Development Kit (JDK)
   - Node.js and npm
   - Docker
   - Jupyter Notebook (for data science components)

## 📈 Features

- Advanced credit risk prediction
- Market analysis and prediction
- Real-time monitoring and metrics
- Centralized configuration management
- Modern web interface for financial management
- Microservices architecture for scalability

## 🧩 DevOps Pipelines

### Front-end Pipeline

The front-end pipeline uses Jenkins as the CI/CD tool. It includes the following stages:

1. Checkout code from Git repository

2. Install Node.js dependencies

3. Build Angular application

4. Execute static code analysis with SonarQube

5. Create Docker image

6. Push Docker image to ECR

7. Deploy to EKS cluster

![frontend drawio](https://github.com/user-attachments/assets/79427a30-0495-4e7a-be55-7a8446867d7b)


### Backend Pipeline  

The backend pipeline also uses Jenkins. Key stages:

1. Checkout code 

2. Run Maven build

3. Execute static code analysis with SonarQube

4. Build Docker image

5. Push image to ECR

6. Deploy to EKS cluster

![pipeline-diagram copy](https://github.com/user-attachments/assets/00eeb718-17c5-4381-85d6-847264a53ca2)


## 🗺️ AWS Architecture

The application is deployed on AWS, leveraging services like:

- VPC for network isolation

- RDS for POSTGRESQL and MYSQL databases

- EC2 for hosting the microservices

- EKS for container orchestration

- ECR for Docker image storage

- CloudWatch and Prometheus for monitoring

![WhatsApp Image 2025-01-21 at 15 52 10](https://github.com/user-attachments/assets/bef98c59-4a9b-452c-a86b-8e837ad695e0)


## 🎨 Front-end UI

The fintech-web-client component provides a modern, feature-rich web interface built with Angular. Key UI elements include:


![photo-collage png (1)](https://github.com/user-attachments/assets/0f98f849-5f78-4004-a1d5-b9bca8b44b2d)




## 👥 Team

| Avatar                                                                                                  | Name | Role | GitHub |
|---------------------------------------------------------------------------------------------------------|------|------|--------|
| <img src="https://github.com/zachary013.png" width="50" height="50" style="border-radius: 50%"/>        | Zakariae Azarkan | DevOps Engineer | [@zachary013](https://github.com/zachary013) |
| <img src="https://github.com/goalaphx.png" width="50" height="50" style="border-radius: 50%"/>          | El Mahdi Id Lahcen | Frontend Developer | [@goalaphx](https://github.com/goalaphx) |
| <img src="https://github.com/hodaifa-ech.png" width="50" height="50" style="border-radius: 50%"/>       | Hodaifa | Cloud Architect | [@hodaifa-ech](https://github.com/hodaifa-ech) |
| <img src="https://github.com/khalilh2002.png" width="50" height="50" style="border-radius: 50%"/>       | Khalil El Houssine | Backend Developer | [@khalilh2002](https://github.com/khalilh2002) |
| <img src="https://github.com/Medamine-Bahassou.png" width="50" height="50" style="border-radius: 50%"/> | Mohamed Amine BAHASSOU | ML Engineer | [@Medamine-Bahassou](https://github.com/Medamine-Bahassou) |


## 🤝 Contributing

We welcome contributions! Please read our contribution guidelines before submitting pull requests.

## 📄 License

Each repository has its own license. Please check individual repositories for specific license information.

## 📞 Contact

For any queries or support, please open an issue in the relevant repository.

---

Built with ❤️ by the Fintech-LSI team
