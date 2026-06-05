# Spam / Phishing Email Detection using Machine Learning

## Project Overview

This project is a beginner-friendly academic artificial intelligence capstone focused on detecting **spam** and **phishing-like emails** using **machine learning**.

The system analyzes the text content of emails and predicts whether a message is:

- `0`: Ham (legitimate email)
- `1`: Spam (unwanted or suspicious email)

The project demonstrates a complete introductory AI workflow:

- data loading
- exploratory data analysis
- text preprocessing
- feature extraction with TF-IDF
- model training
- model evaluation
- custom email prediction

## Academic Information

- **Course:** Artificial Intelligence
- **Academic Year:** 2025-2026
- **Instructor:** Pr. Soufiane HAMIDA

## Team Members

- Mohamed Reda El Ghazouani
- Anass Bentaib
- Chahin Boudra
- Youssef Saoud

## Project Files

- [spam_email_detection_notebook.ipynb](C:/Users/NITRO/Desktop/test/spam_email_detection_notebook.ipynb): final notebook for submission
- [emails.csv](C:/Users/NITRO/Desktop/test/emails.csv): dataset used in the project

## Dataset Description

The dataset contains two columns:

- `text`: the content of the email
- `spam`: the target label

Label meaning:

- `0` = ham / not spam
- `1` = spam

## Methods Used

This project uses simple and suitable methods for a first AI course:

- **Text preprocessing**
  - lowercase conversion
  - extra space removal
  - missing value handling
- **Feature extraction**
  - TF-IDF Vectorizer
- **Classification models**
  - Multinomial Naive Bayes
  - Logistic Regression

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

## Main Goal

The main objective is to show how machine learning can be applied to a real-world text classification problem in a clear and understandable way, without using deep learning or advanced NLP methods.

## How to Run

1. Open the notebook `spam_email_detection_notebook.ipynb` in **Jupyter Notebook**, **JupyterLab**, or **Google Colab**.
2. Make sure the dataset `emails.csv` is available.
3. Run the notebook cells from top to bottom.
4. Use the final demo cell to test a custom email message.

## Libraries Used

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

## Project Limitations

- The model depends on the quality of the dataset.
- Some legitimate emails may be predicted as spam.
- This is a student project with simple preprocessing and baseline models.
- Performance may improve with larger datasets and additional feature engineering.

## Conclusion

This project presents a complete and beginner-friendly machine learning pipeline for spam email detection. It shows that even simple models such as Naive Bayes and Logistic Regression can be effective for classifying email text and can serve as a strong foundation for understanding practical AI applications.
