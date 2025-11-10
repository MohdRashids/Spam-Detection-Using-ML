 Fake News (or Spam) Detection Using Machine Learning  
 📘 *Project Overview*  
This project aims to identify and classify fake or spam messages using *Natural Language Processing (NLP)* and *Machine Learning* techniques.  
It preprocesses text data, extracts features using *TF–IDF (Term Frequency–Inverse Document Frequency), and trains a **Random Forest Classifier* to distinguish between real and fake/spam messages with high accuracy.  

---

 ⚙ *Features*  
- Text data preprocessing (cleaning, tokenization, stopword removal, etc.)  
- Feature extraction using *TF–IDF Vectorizer*  
- Model training using *Random Forest Classifier*  
- Evaluation using accuracy, precision, recall, and F1-score  
- Predicts whether a given message/news is *real or fake (ham or spam)*  

---

 🧾 *Dataset*  
The dataset contains labeled messages categorized as *spam* or *ham (real)*.  
- File used: spam.csv  
- Columns: label, message  

Example:
| Label | Message |
|--------|----------|
| ham | Hey, are you free today? |
| spam | Congratulations! You’ve won a free prize! |

---

### 🧩 *Workflow*  
1. *Import libraries* (pandas, sklearn, nltk, etc.)  
2. *Load the dataset* (spam.csv)  
3. *Preprocess text data* (cleaning + tokenizing)  
4. *Convert text to numeric form using TF–IDF*  
5. *Train the Random Forest model*  
6. *Evaluate the model* (accuracy, confusion matrix)  
7. *Predict on new data*

---

 🧠 *Tech Stack Used*  
- Python  
- Scikit-learn  
- Pandas  
- NumPy  
- NLTK  

---

 📊 *Model Performance (Example)*  
| Metric | Score |
|--------|--------|
| Accuracy | 0.97 |
| Precision | 0.96 |
| Recall | 0.95 |

---
*Mohd Rashid*  
> Passionate about Machine Learning and Data Science.  
> Exploring how AI can make information more trustworthy.
