# Text_Emotion_Detection
This project focuses on detecting human emotions from textual data using various Machine Learning algorithms. The model classifies emotions such as **joy, fear, anger, sadness, disgust, shame, and guilt** based on text input.

---

## 🧠 Overview

Emotion detection from text helps in understanding human sentiments, which can be applied in areas like social media analysis, customer feedback systems, and chatbots.  
The project explores multiple classification algorithms and evaluates their performance.

---

## ⚙️ Tools & Technologies Used

- **Python**
- **Jupyter Notebook / Google Colab**
- **pandas**, **NumPy**
- **scikit-learn**
- **NLTK** for text preprocessing
- **Matplotlib**, **Seaborn** for visualization

---

## 🧩 Project Workflow

1. **Data Preprocessing**
   - Removed stopwords, punctuation, and special symbols using Regex and NLTK.
   - Tokenized and normalized text for efficient model training.

2. **Feature Extraction**
   - Used **Bag of Words (BoW)** and **TF-IDF Vectorization** to convert text into numerical features.

3. **Model Training**
   - Implemented multiple algorithms:
     - Support Vector Machine (SVM)
     - Random Forest Classifier
     - Decision Tree Classifier

4. **Model Evaluation**
   - Compared model performances using **accuracy**, **precision**, **recall**, and **confusion matrix**.

5. **Results**
   - Achieved strong accuracy in predicting emotions, with SVM performing best among tested models.

---

## 📊 Results & Insights

- The model effectively classifies text into multiple emotion categories.  
- Visualization of confusion matrices and accuracy scores shows clear distinctions in model performance.  
- Can be further integrated into sentiment analysis pipelines or chatbot systems.

---
