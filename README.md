Email Classification Using Support Vector Machine (SVM)
This project implements an SVM-based machine learning system to classify emails by analyzing their subject lines and message bodies.

📌 Objective
To build a scalable and accurate model that classifies emails into predefined categories—useful for spam filtering, email triaging, and automation.

📊 Dataset
A CSV file containing:

Subject: Email subject line

Text: Email body

Type: Target label/class

🛠 Preprocessing
Converted text to lowercase

Removed punctuation and numbers

Cleaned subject and body text

Combined them into a new feature: combined_text

🧠 Feature Extraction
Used TF-IDF vectorization (max 5000 features) to convert text into numerical form.

🤖 Model Training
Classifier: Support Vector Machine (SVM) with linear kernel

Dataset split: 80% training / 20% testing

📈 Evaluation
Evaluated with accuracy, precision, recall, and F1-score

💾 Model Saving
svm_model.pkl: Trained SVM model

tfidf_vectorizer.pkl: TF-IDF vectorizer

🧩 Why SVM?
Excellent performance on text data

Handles high-dimensional spaces well

Effective for both binary and multi-class classification

✅ Conclusion
The SVM-based classifier effectively categorizes emails with high accuracy and can be deployed for real-world tasks like spam filtering, customer service, and email automation
