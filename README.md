# Breast Cancer Classification using Neural Networks

This project demonstrates a simple deep learning model to classify breast cancer tumors as **benign** or **malignant** using the **Wisconsin Breast Cancer Dataset**.

## 📊 Dataset
- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- Features: 30 numerical features computed from a digitized image of a breast mass.
- Target: `0 = Malignant`, `1 = Benign`

## 🧠 Model Overview
- Type: Fully Connected Neural Network (Sequential model)
- Framework: Keras with TensorFlow backend
- Architecture:
  - Input layer: 30 features
  - Hidden layers: Dense layers with ReLU activation
  - Output layer: 1 neuron with sigmoid activation

## 🔧 Implementation Steps
1. Loaded and cleaned the dataset (removed nulls, encoded labels).
2. Scaled features using `StandardScaler`.
3. Built a neural network using Keras Sequential API.
4. Trained and validated the model.
5. Evaluated model performance using accuracy, loss, and visualizations.

## 📈 Results
- Achieved high accuracy in predicting tumor classes.
- Visualization of training/validation loss and accuracy included.

## 🛠️ Technologies Used
- Python
- Keras & TensorFlow
- Pandas, NumPy
- Scikit-learn
- Matplotlib

## 📂 How to Run
1. Install required libraries: `pip install -r requirements.txt`
2. Open the notebook: `DL_project_Breast_Cancer_Classification_with_NN.ipynb`
3. Run all cells to train and evaluate the model
