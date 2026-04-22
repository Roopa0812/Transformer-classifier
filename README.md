# 🧠 Transformer-Based News Classification (Deep Learning Project)

## 📌 Overview

This project implements a **Transformer-based deep learning model** for classifying news articles from the **Reuters dataset** into multiple categories.

The main goal is to explore how **Transformer architectures** perform in Natural Language Processing (NLP) tasks and to analyze how increasing model depth affects performance.

---

## 🚀 Key Features

* 🔹 Built using **TensorFlow & Keras**
* 🔹 Custom **Token + Positional Embedding layer**
* 🔹 Implementation of **Transformer blocks**
* 🔹 Dynamic model architecture (3, 5, 7 layers)
* 🔹 Performance comparison using **F1-score**
* 🔹 Visualization using **Confusion Matrix**

---

## 🧩 Problem Statement

Classify news articles into predefined categories using deep learning techniques.

* **Input:** News text
* **Output:** Category label (multi-class classification)

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib / Seaborn
* Scikit-learn

---

## 📂 Dataset

* **Reuters Dataset** (available in Keras)
* Preprocessed using:

  * Vocabulary size: `10,000`
  * Sequence padding: `max length = 200`

---

## 🏗️ Model Architecture

### 1. Token & Positional Embedding

* Converts words into dense vectors
* Adds positional information to retain word order

### 2. Transformer Block

Each block consists of:

* Multi-head Self Attention
* Feed Forward Network
* Layer Normalization
* Dropout

### 3. Model Variants

The model is built with different depths:

* ✅ 3 Transformer layers
* ✅ 5 Transformer layers
* ✅ 7 Transformer layers

---

## ⚙️ Training Details

* Loss Function: `Sparse Categorical Crossentropy`
* Optimizer: `Adam`
* Epochs: `10`
* Batch Size: Default (Keras)

---

## 📊 Evaluation Metrics

* Accuracy
* **F1-Score (Primary Metric)**
* Confusion Matrix

---

## 📈 Results & Insights

* Performance improves with increased model depth up to a certain point
* F1-score provides better evaluation for multi-class classification
* Confusion matrix helps identify misclassified categories

---

## 🧪 Experimentation

| Model Layers | Observation                      |
| ------------ | -------------------------------- |
| 3 Layers     | Faster, lower accuracy           |
| 5 Layers     | Balanced performance             |
| 7 Layers     | Higher accuracy but more complex |

---

## 💡 Key Learnings

* Understanding of **Transformer architecture**
* Importance of **attention mechanisms** in NLP
* Data preprocessing techniques for text
* Model evaluation using **F1-score vs Accuracy**
* Impact of model depth on performance

---

## 🔮 Future Improvements

* Use pretrained models like **BERT**
* Hyperparameter tuning
* Increase dataset size
* Apply regularization techniques

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run the notebook

```bash
jupyter notebook
```

---

## 📌 Project Structure

```
├── ROOPA_DL_PROJECT.ipynb
├── README.md
├── requirements.txt (optional)
```

---

## 🙋‍♀️ Author

**Roopa Reddy**
B.Tech – Computing & Data Science

---

## ⭐ Conclusion

This project demonstrates the power of **Transformer-based models** in text classification and highlights how architectural choices impact performance in deep learning systems.

---
