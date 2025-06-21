# 🌳 Decision Tree Classifier on Bank Marketing Data

This project is **Task 3** of my internship at **SystemTron** as a **Generative AI Intern**.  
In this project, I built a **Decision Tree Classifier** to predict whether a customer will **subscribe to a term deposit**, based on the **Bank Marketing Dataset** provided as nested ZIP files.

---

## 📂 Project Overview

- ✅ Extracted and handled **nested ZIP files** programmatically in Google Colab  
- 🧼 Encoded **categorical features** using `LabelEncoder`  
- 🌳 Trained a **Decision Tree Classifier** using **entropy criterion**  
- 📊 Evaluated model using **confusion matrix**, **classification report**, and **accuracy score**  
- 👁️ Visualized both the **target distribution** and the **entire decision tree**

---

## 📁 Dataset Info

- Source: `bank+marketing.zip`  
- Inner ZIP: `bank.zip`  
- CSV: `bank-full.csv`  
- Target Variable: `y` → Term deposit subscription (`yes` / `no`)

---

## 🛠️ Tools & Libraries

- Python
- pandas, numpy
- seaborn, matplotlib
- scikit-learn
- Google Colab

---

## 🔍 Key Steps

| Step | Description |
|------|-------------|
| 📦 ZIP Handling | Extracted inner ZIPs using `zipfile` |
| 🧪 EDA | Countplot of target distribution |
| 🔠 Label Encoding | Encoded all object-type columns |
| ✂️ Train-Test Split | 80% training, 20% testing with stratification |
| 🧠 Model | `DecisionTreeClassifier(criterion='entropy', max_depth=5)` |
| 📊 Evaluation | Accuracy, Classification Report, Confusion Matrix |
| 🌳 Tree Plot | Visualized entire decision tree with `plot_tree()` |

---

## 📈 Sample Output

- **Accuracy:** ~88% (depends on random state)
- **Confusion Matrix:** Shows actual vs predicted term deposit subscriptions
- **Tree Visualization:** Helps interpret how decisions are made

---

## 👩‍💻 Author

**Sangamithra D**  
B.E. Computer Science & Engineering  
KCG College of Technology  
**Intern @ SystemTron – Generative AI Track**  
🔗 [LinkedIn]https://www.linkedin.com/in/sangamithra-d-8a4092301?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app

---


## 🙏 Acknowledgements

Thanks to **Team SystemTron** for the learning opportunity through real-world datasets and hands-on ML tasks.

---

## 🔖 Tags

`#MachineLearning` `#DecisionTree` `#BankMarketing` `#AIInternship` `#SystemTron` `#Python` `#Colab` `#DataScience`
