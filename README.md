# 💧 Water Potability Prediction Using Machine Learning and Deep Learning

This project uses multiple machine learning and deep learning techniques to predict the **potability of water** based on physicochemical parameters. It includes supervised classification, unsupervised clustering, heuristic feature selection, and a deep neural network.

## 📁 Dataset

The dataset used contains water quality parameters with the target variable:
- `Potability`: `1` (Safe to drink), `0` (Not safe)

[Source: Kaggle – Water Potability Dataset](https://www.kaggle.com/datasets/adityakadiwal/water-potability)

## 🧪 Features

- `ph`: pH value  
- `Hardness`: Water hardness (calcium & magnesium)  
- `Solids`: Total dissolved solids  
- `Chloramines`: Chloramine concentration  
- `Sulfate`: Sulfate concentration  
- `Conductivity`: Electrical conductivity  
- `Organic_carbon`: Organic carbon content  
- `Trihalomethanes`: Chlorination by-products  
- `Turbidity`: Clarity of the water  
- `Potability`: Target variable

## 🧠 Techniques Used

### 🔍 1. Classification
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- XGBoost Classifier

### 🧩 2. Clustering
- KMeans
- DBSCAN
- PCA for visualization

### ⚙️ 3. Heuristic Search
- Recursive Feature Elimination (RFE) for optimal feature subset selection

### 🤖 4. Deep Learning
- Feedforward Neural Network (using TensorFlow/Keras)
- Class imbalance handled using class weights

## 📊 Outputs
- Classification reports for all models
- Accuracy and loss graphs for deep learning
- Cluster visualization using PCA
- Feature importance and selection insights

## 📂 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/skumbarusd/Module_2_Group_5.git
   cd Module_2_Group_5
2. Install Dependencies
   pip install -r requirements.txt
3. Place the dataset (water_potability.csv) in the root directory and update the path in the load dataset section of Water_potability_prediction.ipynb
4. Run contents of Water_potability_prediction.ipynb in Google colab or pycharm
