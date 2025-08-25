# 🏥 Predictive Healthcare Claims Fraud Detection

## 📖 Project Overview
Healthcare fraud is a **multi-billion-dollar problem**. Fraudulent claims can drain resources from patients who truly need them.  
This project leverages **Machine Learning** to predict and detect potential fraudulent claims in healthcare datasets.

---

## 🎯 Goals
- Perform **data cleaning** and **exploratory data analysis (EDA)** to uncover hidden insights.  
- Use **classification models** (Logistic Regression, Random Forest) for fraud detection.  
- Evaluate performance with **Accuracy, Precision, Recall, F1-score, and ROC-AUC**.  
- Demonstrate challenges of **imbalanced data** (fraud cases are rare in real life).  

---

## 🛠️ Tech Stack
- **Python** 🐍  
- **Pandas** → Data cleaning & preprocessing  
- **Matplotlib & Seaborn** → Interactive and attractive visualizations  
- **Scikit-learn** → Model training and evaluation  

---

## 📊 Exploratory Data Analysis (EDA)
Key visualizations performed:  
- Distribution of **claim amounts** for fraud vs. non-fraud.  
- **Correlation heatmap** to check relationships among features.  
- Fraud vs. non-fraud class imbalance visualization.  

📌 Example: Fraudulent claims are much fewer compared to legitimate claims, making fraud detection a **needle-in-a-haystack problem**.

---

## 🤖 Model Building
Two models were built:  
1. **Logistic Regression** – baseline model.  
2. **Random Forest Classifier** – improved performance on complex relationships.  

The dataset showed **severe imbalance**, so while accuracy reached **94%**, the model struggled with fraud recall.  
This highlights **real-world fraud detection challenges** where false negatives are costly.  

---

## 📈 Results
- **Accuracy:** 94%  
- **Precision (Fraud):** Low (due to imbalance)  
- **Recall (Fraud):** Needs improvement (model missed some fraud cases)  
- **ROC-AUC:** ~0.48  

✅ Great accuracy, but 🚨 limited fraud detection capability → a realistic outcome for fraud datasets.  

---

## 🌟 Future Improvements
- Use **SMOTE / class weighting** to handle imbalanced data.  
- Try advanced algorithms like **XGBoost / LightGBM**.  
- Deploy as a **dashboard or API** for real-time fraud detection.  

---

---

## ✨ Key Takeaways
- Fraud detection is **high-stakes** and **imbalanced**.  
- High accuracy does not always mean a good model — recall is crucial.  
- This project demonstrates **real-world data science trade-offs**.  

---

## 👩‍💻 Author
**Kareem Basha Shaik**  
📌 Aspiring Data Analyst | Passionate about AI & Predictive Analytics  
🔗 [LinkedIn](https://www.linkedin.com) | [GitHub](https://github.com) |   [GitHub](https://github.com)
