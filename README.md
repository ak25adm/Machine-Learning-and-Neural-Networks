# Machine-Learning-and-Neural-Networks
# Backpropagation Impact Study using Neural Networks  
### (Car Price Prediction & Diabetes Classification)

This project demonstrates the **effect of backpropagation (training iterations / epochs)** on the performance of neural networks across two different real-world problems:

- Car Price Prediction (Regression)
- Diabetes Prediction (Classification)

The core objective is to **prove that increasing backpropagation (epochs) improves model performance**, and this is validated experimentally on both datasets.

---

## 🚀 How to Run

**Clone repository**
```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
run jupyter notebook
```

---

## Project Objective

Rather than just building models, this project focuses on:

>  *Understanding how neural networks learn over time through backpropagation*

We experimentally show that:

- Increasing epochs → better weight updates  
- Better weight updates → reduced error  
- Reduced error → improved predictions  

This trend is consistently observed in **both regression and classification tasks**.

---

## 📊 Datasets Used

### 1. Car Price Dataset
- Type: Regression  
- Goal: Predict car prices  
- Metric: Mean Absolute Error (MAE), Loss  

### 2. Diabetes Dataset
- Type: Classification  
- Goal: Predict whether a patient has diabetes  
- Metric: Accuracy, Loss  

---

## 🛠️ Technologies Used

- Python  
- TensorFlow / Keras  
- Scikit-learn  
- Pandas  
- Matplotlib  

---

## ⚙️ Workflow

1. Data Loading & Cleaning  
2. Feature Scaling (important for neural networks)  
3. Train-Test Split  
4. Model Creation (Deep Neural Network)  
5. Training with different epochs  
6. Performance Comparison  

---

## 🧠 Model Architecture

- Fully connected (Dense) neural network  
- ReLU activation for hidden layers  
- Output layer:
  - Regression → Linear  
  - Classification → Sigmoid  

---

## 🔁 Core Concept: Backpropagation

Backpropagation is the learning mechanism of neural networks where:

- Errors are calculated
- Gradients are computed
- Weights are updated iteratively

👉 In this project, we **increase the number of epochs** to allow:

- More backpropagation cycles  
- Better learning of patterns  
- Gradual performance improvement  

---

## 📈 Experimental Results

### 🚗 Car Price Prediction (Regression)

| Epochs | Observation |
|--------|------------|
| 10     | Very high loss, poor predictions |
| 50     | Noticeable improvement |
| 100    | Significant error reduction |
| 300    | Much better MAE |

✅ Conclusion:  
More epochs → lower MAE → better predictions  

---

### 🩺 Diabetes Prediction (Classification)

| Epochs | Observation |
|--------|------------|
| Low    | Lower accuracy |
| Medium | Improved classification |
| High   | Better accuracy and stability |

✅ Conclusion:  
More epochs → higher accuracy → better classification  

---

## 🔍 Key Insight (Main Contribution)

> 💡 **Backpropagation effectiveness is directly tied to training duration (epochs)**

Across both datasets:

- Neural networks improve **consistently** with more epochs  
- Learning is **progressive**, not instant  
- Proper training time is critical for performance  

---

## ⚠️ Important Note

While increasing epochs improves performance:

- Too many epochs may lead to **overfitting**  
- Proper balance is required  

---

