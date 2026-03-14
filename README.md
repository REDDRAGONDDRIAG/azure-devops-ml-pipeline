# Project Overview

This project is designed to streamline machine learning pipelines using Azure DevOps, focusing on automation and reproducibility of ML workflows.

# Architecture

The architecture consists of three main layers:
1. Data Ingestion
2. Model Training and Validation
3. Deployment and Monitoring

# Features
- Automated data preprocessing
- Support for multiple ML algorithms
- Built-in model evaluation metrics
- Seamless Azure integration for deployment

# Technologies
- Python
- Azure DevOps
- Azure Machine Learning
- Docker


# Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/REDDRAGONDDRIAG/azure-devops-ml-pipeline.git
   cd azure-devops-ml-pipeline
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up Azure credentials as described in the Azure documentation.

# Usage Examples
```bash
# Run data ingestion
python src/ingestion/run.py

# Train model
python src/training/train.py
```

# Contributing Guidelines
We welcome contributions! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a clear description of your changes.
