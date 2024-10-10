Resume Parsing System

A. Introduction

This system is designed to automate the process of parsing and analyzing resumes from various fields. It aims to assist HR departments and recruitment teams in understanding trends and extracting key information from a collection of resumes.

B. Solution Outline
1. Data Loading: The system loads a dataset consisting of resumes in CSV format. Each entry includes details such as category and resume text.
2. Data Cleaning:
   - Cleans resume text by removing URLs, social media tags, and extra spaces.
   - Standardizes the text for further analysis.
3. Data Analysis:
   - Analyzes the distribution of resumes across different categories to identify trends.
   - Extracts keywords to determine common skills and qualifications.
4. Visualization:
   - Generates bar plots and pie charts to visualize the distribution of resumes by category.
   - Creates WordClouds to highlight frequently occurring terms and skills in the resumes.

C. Example Input and Output
- Input: A CSV file named `UpdatedResumeDataSet.csv` containing columns for category and resume text.
- Output:
   - Visual plots showing the distribution of resumes by category.
   - WordCloud images depicting common words and phrases found in the resumes.

D. Setup and Running

1. Requirements
- Python 3.x
- Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn, nltk, wordcloud
- Dataset: The system expects a CSV file named `UpdatedResumeDataSet.csv`.

2. Installation
To set up the system, install the required libraries using the following command:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn nltk wordcloud
```

3. Running the Script
To run the script, navigate to the script's directory and execute it with Python:
```bash
python Resume_Parsing.py
```

4. Dataset
The dataset should be in CSV format and located in the same directory as the script. You can download the dataset from the following link:
[Download Dataset](https://www.kaggle.com/datasets/gauravduttakiit/resume-dataset)

E. Additional Information
- The script includes data cleaning and preprocessing steps that are essential for accurate analysis.
- Ensure that NLTK resources are downloaded as prompted by the script, which are required for text processing.
- For troubleshooting, ensure all libraries are correctly installed and the dataset is properly formatted.
