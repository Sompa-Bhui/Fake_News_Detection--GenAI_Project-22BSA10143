# 📰 Fake News Detector — GEN AI Project  

Fake News Detector

By
Sompa Bhui (22BSA10143) 

## 📌 Overview

This repository contains a Fake News Detection project developed as part of the **GEN AI** course under the NLP module. The goal is to classify news articles as **fake** or **real** using Natural Language Processing (NLP) and a Logistic Regression model. The project is trained on the **Kaggle Fake and Real News Dataset**, achieving an accuracy of around **92%**.

The implementation is adapted from advanced fake news detection workflows (originally involving BERT and LSTM) and simplified for educational clarity and accessibility.

## 📂 Project Structure

- `my_fake_news_detection.ipynb` – Main Jupyter Notebook with implementation  
- `confusion_matrix.png` – Visualization of model performance  
- `explanation.md` – Phase 2 brief implementation summary  
- `report.tex` – Phase 3 final LaTeX report

  Instructions

1.	Clone the Repository:
2.	git clone https://github.com/Sompa-Bhui/Fake_News_Detection--GenAI_Project-22BSA10143.git
3.  cd Fake_News_Detection--GenAI_Project-22BSA10143
4.	Set Up Environment:
o	Ensure Python 3.8+ is installed.
o	Install required libraries:
pip install pandas nltk scikit-learn numpy seaborn matplotlib
5.	Download the Dataset:
o	The Kaggle Fake and Real News Dataset (Fake.csv, True.csv) is not included due to file size limits. Download it from Kaggle.
o	Place the files in a data/ subfolder:
o	Fake_News_Detection--GenAI_Project-22BSA10143.csv
Fake_News_Detection--GenAI_Project-22BSA10143.csv
6.	Run the Notebook:
o	Open my_fake_news_detection.ipynb in Jupyter Notebook:
jupyter notebook my_fake_news_detection.ipynb
o	Execute all cells (Cell > Run All) to preprocess the data, train the model, and generate results.


Output
•	Accuracy: 92%
•	Classification Report:
o	Fake: Precision: 0.91, Recall: 0.93, F1-score: 0.92
o	True: Precision: 0.93, Recall: 0.91, F1-score: 0.92
•	Visualization: Confusion matrix saved as confusion_matrix.png.
•	Sample Prediction: "Government claims new policy boosts economy, lacks evidence." → Fake


Notes
• This implementation is a simplified and accessible version designed specifically for educational use in the GEN AI course.

• It uses Logistic Regression instead of more complex models like BERT or LSTM, ensuring compatibility with standard systems and easier interpretability.

• All results were obtained by running the notebook on a standard laptop, highlighting its practicality and efficiency for coursework and learning.

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/Sompa-Bhui/Fake_News_Detection--GenAI_Project-22BSA10143.git
cd Fake_News_Detection--GenAI_Project-22BSA10143

