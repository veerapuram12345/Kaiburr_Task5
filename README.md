# 📝 Consumer Complaint Text Classification

This project applies **Natural Language Processing (NLP)** and **Machine Learning** techniques to classify consumer complaints into predefined categories using the [Consumer Complaint Database](https://catalog.data.gov/dataset/consumer-complaint-database).

---

## 🎯 Objective  
The goal is to build a **multi-class text classification model** that categorizes complaints into the following categories:

- **0** → Credit reporting, repair, or other  
- **1** → Debt collection  
- **2** → Consumer Loan  
- **3** → Mortgage  

---

## 📊 Project Workflow  

1. **Exploratory Data Analysis (EDA) & Feature Engineering**  
   - Analyzed complaint text distribution, class balance, and most frequent words.  
   - Engineered features such as text length and word counts.  

2. **Text Pre-processing**  
   - Lowercasing text  
   - Removing stopwords, punctuation, and special characters  
   - Tokenization & Lemmatization  
   - Text vectorization using **TF-IDF**  

3. **Model Selection**  
   - Implemented and compared multiple models:  
     - Logistic Regression  
     - Naïve Bayes  
     - Random Forest  
     - Support Vector Machine (SVM)  

4. **Model Evaluation**  
   - Metrics: **Accuracy, Precision, Recall, F1-score**  
   - Visualized classification results with a confusion matrix  

5. **Prediction**  
   - Built a pipeline to predict complaint categories for new unseen text  

---

## 🛠️ Tech Stack  

- **Python 3.x**  
- **Jupyter Notebook**  
- **Libraries**:  
  - pandas  
  - numpy  
  - scikit-learn  
  - nltk  
  - matplotlib  
  - seaborn  

---

## 📂 Repository Structure  


---

## ⚙️ Installation  

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/consumer-complaint-classification.git
cd consumer-complaint-classification
pip install -r requirements.txt

🚀 Usage

Run the Jupyter Notebook:

jupyter notebook Kaiburr_Task5.ipynb

📌 Dataset

The dataset is publicly available here:
🔗 https://catalog.data.gov/dataset/consumer-complaint-database


Author

Developed by Veerapuram Naga Divya Sree

© 2025 Kaiburr LLC. All rights reserved
