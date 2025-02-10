# Resume Parsing and Analysis using NLP Techniques

---

## 📌 Project Overview
This project aims to automate the extraction and analysis of resume data using **Natural Language Processing (NLP) techniques**. It assists HR professionals and recruitment teams in processing resumes efficiently, extracting key details like **education, experience, and skills**, and analyzing them to support better hiring decisions.

### 🎯 Objectives
- Develop an **automated resume parser** for structured extraction.
- Use **NLP techniques** to extract key attributes (education, skills, experience).
- Implement **classification models** to categorize resumes into job roles.
- **Visualize** trends in job applications across industries.
- Provide insights for **data-driven hiring decisions**.

---

## 📂 Project Files
- **📄 Project Report:** `AIT526_Team7_AB_BT_MR_VR_Final_Report.pdf`
- **📓 Jupyter Notebook:** `Resume_Parsing_and_Analysis_using_NLP_Techniques.ipynb`
- **🌍 HTML Report:** `Resume_Parsing_and_Analysis_using_NLP_Techniques.html`

---

## 📊 Dataset Information
- **Format:** CSV file (`UpdatedResumeDataSet.csv`)
- **Columns:**
  - `Category`: Job role classification (e.g., Data Science, Software Development).
  - `Resume`: Text content of the resume.
- **Source:** [Kaggle Resume Dataset](https://www.kaggle.com/datasets/gauravduttakiit/resume-dataset)

---

## 🛠️ Project Workflow
1. **Data Loading:** Load resume data in CSV format.
2. **Data Preprocessing:**
   - Remove **URLs, social media tags, special characters**.
   - Tokenize text and apply **stop-word removal**.
   - Convert text to **lowercase** for standardization.
3. **Feature Engineering:**
   - Use **TF-IDF** for text vectorization.
   - Apply **Named Entity Recognition (NER)** to extract entities (skills, job titles).
4. **Machine Learning Models:**
   - **Classification:** Categorize resumes into job roles using **Naïve Bayes, SVM**.
   - **Clustering:** Identify patterns in skill sets using **K-Means**.
5. **Visualization:**
   - Generate **bar charts** for resume distribution across categories.
   - Use **WordCloud** to highlight frequently used keywords.
6. **Model Evaluation:**
   - **Accuracy, Precision, Recall, F1-Score** for classification models.
   - Confusion matrix to validate predictions.

---

## 📈 Results & Analysis
- **High Accuracy in Resume Classification** using **SVM & Naïve Bayes**.
- **Key Skills Identified** in each job category.
- **Strong Correlations** between job roles and specific skill sets.
- **Effective Automation** in resume parsing and keyword extraction.

---

## 🏆 Conclusion
- **Automating resume parsing** saves **time and resources** in recruitment.
- **NLP techniques** effectively extract and categorize candidate profiles.
- **Improved hiring efficiency** by reducing manual screening effort.

### 🚀 Future Enhancements
- Expand dataset with **real-world resumes** for better accuracy.
- Implement **Deep Learning-based NLP models** for **advanced parsing**.
- Develop a **Web API** for real-time **resume screening**.

---

## 📚 References
1. [TF-IDF & Vectorization Techniques](https://scikit-learn.org/stable/modules/feature_extraction.html)
2. [NLTK for Resume Parsing](https://www.nltk.org/)
3. [Machine Learning in NLP](https://scikit-learn.org/)
4. [Kaggle Resume Dataset](https://www.kaggle.com/datasets/gauravduttakiit/resume-dataset)

---

## Team Members
- Akhil Bhimarasetty
- Bhuvan Sai Thatthari
- Mukesh Rajmohan
- Phani Venkata Krishna Varun Vegi Sai Raghavendra

---

## ⚙️ How to Run the Code
### 1️⃣ Prerequisites
- **Python 3.x**
- Required Python Libraries:
  ```bash
  pip install numpy pandas matplotlib seaborn scikit-learn nltk wordcloud

---


This `README.md` provides:
- **Project Summary**
- **Dataset Details**
- **Workflow Explanation**
- **Results & Insights**
- **Execution Instructions**

Let me know if you need any modifications! 🚀
