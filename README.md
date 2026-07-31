# 🏥 End-to-End MedVision AI Platform
### Intelligent Medical Image Classification & Deep Learning System

End-to-End MedVision AI Platform is a powerful deep learning-based system that transforms medical images into meaningful predictions using Convolutional Neural Networks (CNN). It provides a complete machine learning pipeline from data ingestion to deployment, enabling scalable and automated healthcare image analysis.

---

## 🌟 Overview

Medical imaging plays a crucial role in modern healthcare, but analyzing images manually is time-consuming and requires expertise.

MedVision AI solves this problem by:

- Automatically processing medical images  
- Applying deep learning (CNN) for classification  
- Generating accurate predictions  
- Providing real-time inference through APIs  
- Ensuring reproducibility with ML pipelines  

---

## ✨ Key Features

- 🧠 Deep Learning Model (CNN) using TensorFlow  
- 🔄 End-to-End ML Pipeline  
  - Data Ingestion  
  - Base Model Preparation  
  - Model Training  
  - Model Evaluation  
- 🌐 Flask API for real-time prediction  
- 📊 MLflow for experiment tracking  
- 📦 DVC for data and pipeline versioning  
- ⚙️ Modular and production-ready architecture  

---

## 🏗️ Project Architecture


MedVision-AI/
│── app.py # Flask API
│── main.py # ML pipeline execution
│── params.yaml # Model parameters
│── dvc.yaml # Pipeline orchestration
│── requirements.txt # Dependencies
│── setup.py # Package setup
│── scores.json # Model metrics
│── src/
│ └── cnnClassifier/
│ ├── components/ # Core ML components
│ ├── pipeline/ # Training pipeline
│ ├── utils/ # Utility functions
│ ├── config/ # Configuration
│ ├── entity/ # Data entities
│ └── constants/ # Constants
│── templates/
│ └── index.html # Frontend UI


---

## ⚙️ Workflow

1. Load and ingest image dataset  
2. Prepare base CNN model  
3. Train deep learning model  
4. Evaluate model performance  
5. Deploy via Flask API  
6. Serve real-time predictions  

---

## 🛠️ Tech Stack

- Python  
- TensorFlow / Keras  
- Flask  
- MLflow  
- DVC  
- NumPy, Pandas  

---

## 🚀 Getting Started

### Clone Repository


git clone https://github.com/VermaAnkit21/MedVision-AI.git
cd MedVision-AI


### Install Dependencies


pip install -r requirements.txt


### Run Training


python main.py


### Run App


python app.py


---

## 🔌 API

### Train

GET /train


### Predict

POST /predict


#### Request:

{
"image": "base64_encoded_image"
}


#### Response:

{
"prediction": "class_label"
}


---

## 📊 Model Performance

- Accuracy: 1.0  
- Loss: 0.0022  

---

## 🎯 Use Cases

- Medical Image Diagnosis  
- CT/MRI Detection  
- Healthcare Analytics  
- Clinical Decision Support  

---

## ⚠️ Notes

- Install dependencies first  
- Run DVC using:

dvc repro


---

## 👨‍💻 Author

Ankit Verma  

---

## ⭐ Support

Give a ⭐ if you like this project!
