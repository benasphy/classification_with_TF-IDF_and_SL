# 🚀 AI-Powered Document Classification

## 📌 Overview
This project is an AI-powered document classification system that uses TF-IDF for feature extraction and applies Naïve Bayes and Support Vector Machine (SVM) classifiers to categorize documents efficiently. The goal is to accurately classify new documents into predefined categories using supervised learning techniques.

## 🎯 Features
- 📄 TF-IDF-based feature extraction for transforming text into numerical representations.
- 🧠 Multinomial Naïve Bayes and SVM models for efficient text classification.
- 📊 Performance evaluation using precision, recall, and accuracy metrics.
- 🏆 Support for multiple categories for document classification.
- 🔧 Easy model training and testing pipeline.

---
## 🏗️ How It Works
### 1️⃣ Preprocessing
- Tokenization
- Stopword removal
- TF-IDF vectorization

### 2️⃣ Model Training
- We train Multinomial Naïve Bayes and SVM models using labeled text data.
- Hyperparameter tuning is performed for optimal performance.

### 3️⃣ Classification & Evaluation
- New documents are transformed using TF-IDF.
- Predictions are made using trained models.
- Performance metrics such as accuracy, precision, recall, and F1-score are calculated.

---
## 🤔 Why Naïve Bayes and SVM?
### 1️⃣ Naïve Bayes (Multinomial NB)
✅ Works well with text classification due to its assumption of word independence.
✅ Fast and efficient, even with large datasets.
✅ Handles high-dimensional data effectively.

### 2️⃣ Support Vector Machine (SVM)
✅ Effective for complex decision boundaries.
✅ Works well with high-dimensional sparse data, making it great for TF-IDF representations.
✅ Robust against overfitting, especially in high-dimensional spaces.

By combining these models, we ensure fast, efficient, and accurate classification for various document types.

---
## 🛠️ Installation & Setup
1. Clone the repository:
  
   git clone https://github.com/benasphy/classification_with_TF-IDF_and_SL.git
   
2. Navigate to the project folder:
  
   cd classification_with_TF-IDF_and_SL
   
3. Run the training script:
  
   python classification_with_TF-IDF_and_SL.py
   
   

---
## 🚀 Future Enhancements
- Implement deep learning-based text classification.
- Add topic modeling for better insights.
- Deploy the model as a REST API for real-world applications.

---
## 🤝 Contributing
We welcome contributions! Feel free to open an issue or submit a pull request if you have any improvements.

---
## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

📌 Enjoy classifying documents with AI! 🚀
