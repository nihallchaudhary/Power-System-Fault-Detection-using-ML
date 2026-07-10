# Power System Fault Detection and Classification using Machine Learning

## Overview
This project uses Machine Learning and IBM Cloud to classify power system faults based on electrical and environmental parameters. The system predicts fault types such as Transformer Failure, Overheating, and Line Breakage.

## Technologies Used
- IBM Cloud
- IBM Watson Studio
- IBM Cloud Object Storage
- Python
- Pandas
- Scikit-Learn
- XGBoost
- Gradio

## Dataset Features
- Voltage (V)
- Current (A)
- Power Load (MW)
- Temperature (°C)
- Wind Speed (km/h)
- Weather Condition
- Maintenance Status
- Component Health
- Duration of Fault (hrs)
- Down Time (hrs)

## Fault Classes
- Transformer Failure
- Overheating
- Line Breakage

## Models Used
### Random Forest
Accuracy: 32.35%

### XGBoost
Accuracy: 37.25%

## Project Workflow
Dataset → IBM Cloud Object Storage → Watson Studio → Data Preprocessing → Model Training → Fault Prediction

## Results
- Successfully classified power system faults.
- XGBoost achieved the best accuracy of 37.25%.
- Developed a Gradio-based prediction interface.

### Project Screenshots

#### 1. Dataset Loading from IBM Cloud Object Storage
Shows successful loading and preview of the fault dataset.

### 2. XGBoost Model Training and Accuracy Evaluation
Training the XGBoost classifier and measuring prediction accuracy.

### 3. Fault Type Prediction Result
Example of fault classification using real input parameters.

### 4. Model Performance Evaluation
Classification report showing precision, recall, and F1-score.

### 5. Fault Distribution Analysis
Visualization of different fault categories in the dataset.

### 6. Random Forest vs XGBoost Performance Comparison
Comparison of machine learning model accuracies.

### 7. Power System Fault Classification Web Interface
Interactive Gradio application for real-time fault prediction.

## Repository Contents
- `fault_data.csv` – Dataset
- `Fault_Classification.ipynb` – IBM Watson Studio Notebook
- `Project_Presentation.pptx` – Project PPT
- `Problem_Statement.pdf` – Problem Statement

## Author
Nihal Chaudhary  
B.Tech Electrical Engineering  
NIT Delhi

## Internship
AICTE IBM SkillsBuild Internship 2026
