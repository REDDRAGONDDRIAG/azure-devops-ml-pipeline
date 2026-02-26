# Azure MLOps CI/CD Pipeline

This project demonstrates an end-to-end MLOps workflow on Microsoft Azure using:

- GitHub Actions (CI/CD)
- Terraform (Infrastructure as Code)
- Python (ML training pipeline)
- Pytest (testing)
- Flake8 & Black (code quality)
- Azure environment variables & secrets

## Architecture

1. Developer pushes code
2. GitHub Actions runs:
   - lint & formatting checks
   - tests
   - model training
3. Model artifact is generated and versioned
4. Infrastructure is provisioned using Terraform
