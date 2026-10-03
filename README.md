# VortexTech AI/ML Week 4 – Sentiment Analysis
## Project Overview
This project is part of the VortexTech AI & ML Internship Week 4 Advanced task.
The project focuses on building a **Sentiment Analysis Model** using Natural Language Processing (NLP).
The model classifies text into two categories:
* Positive
* Negative
## Technologies Used
* Python
* Pandas
* Scikit-learn
* NLTK
* Matplotlib
* Seaborn
* TF-IDF
* Logistic Regression
* Jupyter Notebook
## Project Pipeline
The project follows these steps:
1. Load the sentiment dataset.
2. Inspect the dataset and sentiment distribution.
3. Clean and preprocess the text.
4. Convert text into numerical features using TF-IDF.
5. Split the dataset into training and testing sets.
6. Train a Logistic Regression model.
7. Evaluate the model using Accuracy and F1-score.
8. Generate a confusion matrix.
9. Test the model using three custom sentences.
10. Predict whether each sentence is positive or negative.
## Dataset
The project uses a public sentiment-labeled text dataset containing positive and negative examples.
The dataset is stored in:
```text
sentiment_dataset.csv
```
## How to Run
### 1. Clone the repository
```bash
git clone https://github.com/shoaibshabeer/vortextech-aiml-week4.git
```
### 2. Open the project folder
```bash
cd vortextech-aiml-week4
```
### 3. Install required libraries
```bash
pip install pandas scikit-learn nltk matplotlib seaborn
```
### 4. Open the Jupyter Notebook
```bash
jupyter notebook
```
Then open:
```text
Week4_Sentiment_Analysis.ipynb
```
### 5. Run the notebook
Run the cells from top to bottom to:
* preprocess the dataset
* train the model
* evaluate performance
* generate the confusion matrix
* test custom sentences
## Model
The project uses **Logistic Regression** for binary sentiment classification.
Text is converted into numerical features using:
```python
TfidfVectorizer(max_features=5000)
```
## Evaluation
The model is evaluated using:
* Accuracy
* F1-score
* Confusion Matrix
The actual results are generated when the notebook is executed.
## Limitation
The model may have difficulty understanding sarcasm, complex context, or ambiguous language.
The quality of predictions can also depend on the size and quality of the training dataset.
VortexTech AI/ML Internship – Week 4
