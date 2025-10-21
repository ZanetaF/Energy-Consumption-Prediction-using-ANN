# Office Building Energy Consumption Prediction

![Python](https://skillicons.dev/icons?i=python) ![TensorFlow](https://skillicons.dev/icons?i=tensorflow) ![Keras](https://skillicons.dev/icons?i=keras) ![Pandas](https://skillicons.dev/icons?i=pandas) ![Matplotlib](https://skillicons.dev/icons?i=matplotlib)

**Course:** Deep Learning 
**Year:** 2025  


## About This Project
This project aims to build models that predict energy consumption of an office building. The workflow includes Exploratory Data Analysis (EDA), preprocessing, building baseline and modified neural network models (Sequential and Functional), and evaluating them using multiple metrics.


## Dataset Features
The dataset includes features related to building energy usage, such as:
- Temperature, Humidity, Occupancy, Lighting, Equipment Power, etc.
- Energy consumption targets


## Project Workflow

### 1. Exploratory Data Analysis (EDA)
- Analyzed data distribution, missing values, and anomalies  
- Handled outliers, missing values, and normalized/scaled features  
- Split dataset into Train (70%), Validation (10%), and Test (20%)

### 2. Baseline Models
- **Sequential Model:** Minimum 2 hidden layers, ReLU activation, neurons ≥ 2x input dimensions  
- **Functional Model:** Minimum 2 hidden layers, ReLU activation, neurons ≥ 2x input dimensions  
- Trained both models for at least 10 epochs

### 3. Model Modifications
- Adjusted number of neurons and layers, changed activation functions, or fine-tuned hyperparameters  
- Trained 2 modified models based on baseline architectures

### 4. Evaluation
- Evaluated all 4 models using at least 3 metrics (e.g., MAE, RMSE, R²)  
- Compared performance, analyzed results, and concluded best-performing model


## Technologies Used
- Python  
- TensorFlow & Keras  
- pandas & NumPy  
- Matplotlib & Seaborn  
- scikit-learn (for preprocessing & evaluation metrics)

