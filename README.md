# 📌 Finance Complaint Prediction Project

## 📖 Overview
The **Consumer Financial Protection Bureau (CFPB)** is a U.S. agency that mediates disputes between financial institutions and consumers. When a complaint is filed, the agency forwards the issue to the relevant company and requests a response.

This project **analyzes complaint narratives** and **predicts whether a consumer will dispute the resolution or not**. The goal is to help financial institutions prioritize cases that are likely to be disputed, enabling them to take proactive measures to improve customer satisfaction and reduce conflicts.

---

## 🛠️ Tech Stack
- **Programming Language**: Python 🐍
- **Data Processing**: Pandas, NumPy 
- **Machine Learning**: Scikit-learn
- **NLP (Natural Language Processing)**: NLTK, SpaCy
- **Visualization**: Matplotlib, Seaborn
- **Deployment**: Flask/FastAPI (Optional for future development)

---

## 🎯 Use Case
This project classifies consumer complaints based on the **issues described in the complaint text** and other dataset features to predict whether the **consumer will dispute the resolution or not**.

### ✅ **Key Benefits**:
- 📊 **Data-Driven Prioritization**: Helps companies allocate resources efficiently.
- 🎯 **Proactive Dispute Handling**: Enables financial institutions to address high-risk complaints in advance.
- 🔍 **Improved Consumer Satisfaction**: Reduces escalations by predicting potential disputes early.

---

## 📂Dataset Information
### Attributes
The dataset contains consumer complaints along with details such as:
- **Date received** : Date on which Complaint was received .
- **Product** : Product against which complaint was registered .
- **Issue** :  Sumarises the issue is related to what domain . 
- **Company** : Company against which complaint was registered .
- **State** : State in which complaint was registered .
- **Consumer consent provided?** : Whether the consumer provided the consent to make his/her complaint public or not .
- **Submitted via** : Describes the way through which the complaint was registered  .
- **Date sent to company** : Date on which Complaint was forwarded to the company .
- **Company response to consumer** : What type of response was given by the company to the consumer .
- **Timely response?** :  Whether the response given was on a timely basis or  not .
- **Consumer disputed?** :  Whether the consumer Consumer disputed the complaint or not .
-  **Complaint ID**  : Consumer's unique identifier

---

## 📈 Results & Insights
- Dataset has been collected from Consumer Finance US government.
- "Tags" , "Consumer complaint narrative" , "Company public response" , "ZIP code" , "Sub-product" , "Sub-issue"  are the columns that can be removed as don't help
   in the model . 
- "company" its a name column and can be removed as it contains 4284 unique companies and it can't be used in the model . 
- New features like "Months" and "Year" are created which demonstrated a connection between the complaints disputed by customers on monthly and yearly basis . 
- "Issue" is a text column so text processing can be done and vectorized by tfidf for model training . 
- Rows are removed on the basis of columns containing the maximum number of null values to get an acurate analysis results.


---


## Technologies Used: 
- Python
- VS Code
- Juypter Notebook
- MS Excel

---
  
## 🤝 Contribution
Want to improve this project? Follow these steps:
1. Fork the repository 📌
2. Create a feature branch (`git checkout -b feature-xyz`)
3. Commit changes (`git commit -m 'Added new feature'`)
4. Push to your branch (`git push origin feature-xyz`)
5. Open a **Pull Request** ✅



Feel free to explore the Jupyter Notebook or Python scripts to delve into the analysis and outcomes of this project!

**Note:**  The visuals of the analysis are added in the same github repository in the .jpg format . Please have a look at those visuals for more information .






