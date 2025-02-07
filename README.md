![Newspaper Image](https://th.bing.com/th/id/R.162007b767a03299d31e5d1a42cf872c?rik=Wu%2bLXHWLF%2bV4xw&pid=ImgRaw&r=0)
# 📰 News Articles Classification Project


![Python](https://img.shields.io/badge/Python-3.8-blue?style=for-the-badge)  
![MLflow](https://img.shields.io/badge/MLflow-Tracking-orange?style=for-the-badge)  
![Streamlit](https://img.shields.io/badge/Streamlit-Web_App-red?style=for-the-badge)  

## 📌 Table of Contents
- [📌 Overview](#-overview)
- [🚀 Features](#-features)
- [📂 Project Structure](#-project-structure)
- [🛠 Data Cleaning](#-data-cleaning)
- [📊 Exploratory Data Analysis](#-exploratory-data-analysis)
- [🔍 Natural Language Processing](#-natural-language-processing)
- [🤖 Machine Learning Models](#-machine-learning-models)
- [📈 Model Evaluation](#-model-evaluation)
- [🚀 MLflow Experiment Tracking](#-mlflow-experiment-tracking)
- [🌍 Streamlit Deployment](#-streamlit-deployment)
- [📥 Required Downloads](#-required-downloads)
- [📦 Packages](#-packages)
- [🖥️ Environment Setup](#-environment-setup)
- [📊 Dataset Description](#-dataset-description)
- [👥 Team Members](#-team-members)

---

## 📌 Overview
This project classifies news articles into predefined categories using **machine learning** and **natural language processing (NLP)** techniques. It involves **data loading, preprocessing, model training, evaluation, and deployment** via a **Streamlit web app**.

## 📦 Packages
To carry out all the objectives for this repo, the following necessary dependencies were loaded:

- **Pandas** 2.2.2 and **Numpy** 1.26
- **Matplotlib** 3.8.4
- **Seaborn** 0.13.2
- **NLTK** 3.8.1
- **Scikit-Learn** 1.3.2
- **MLflow** 2.7.1
- **Streamlit** 1.27.2

## 🖥️ Environment Setup
It's highly recommended to use a virtual environment for your projects. Below are the steps to set up and activate a Conda environment:

```sh
# Create the new environment (only need to do this once)
conda create --name <env>

# Activate the virtual environment
conda activate <env>

# Install the pip package
conda install pip

# Install the requirements for this project
pip install -r requirements.txt
```

## 📊 Dataset Description
The dataset is comprised of news articles that need to be classified into categories based on their content, including Business, Technology, Sports, Education, and Entertainment.

### Dataset Features:

| Column     | Description                                          |
|------------|------------------------------------------------------|
| Headlines  | The headline or title of the news article.          |
| Description | A brief summary or description of the article.     |
| Content    | The full text content of the news article.          |
| URL        | The URL link to the original source of the article. |
| Category   | The category or topic of the news article.          |

## 🚀 MLflow Experiment Tracking
MLOps (Machine Learning Operations) helps manage and streamline the lifecycle of machine learning models. **MLflow** is used to:
- Track experiments
- Manage models
- Streamline deployment processes

For experimentation, testing, and reproducibility, MLflow logs hyperparameter tuning and compares different model configurations.

📌 Follow the setup guide here: [MLflow Quickstart](https://www.mlflow.org/docs/2.7.1/quickstart.html#quickstart)

## 🌍 Streamlit Deployment
Streamlit is a framework that provides a simple and powerful way to build interactive web applications for machine learning models.

### **Running the Streamlit web app on your local machine**
```sh
pip install -U streamlit numpy pandas scikit-learn nltk mlflow matplotlib seaborn
cd Streamlit
streamlit run base_app.py
```

The app will be available at:
```
Local URL: http://localhost:8501
Network URL: http://192.168.x.x:8501
```

### **Deploying your Streamlit web app**
To deploy your app:
1. Click on **Deploy** in Streamlit Cloud.

## 👥 Team Members
- **Lindelwe Mathonsi**
- **Melokuhle Makhwasa**
- **Lamel Kekana**
- **Sanele Bhembe**
- **Nthabiseng Mokhachane**

