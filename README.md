# Email Spam Classifier
Built an NLP-based email spam classifier to accurately distinguish spam from legitimate messages using text feature extraction and machine learning.

## Business Problem
Businesses need an automated system to accurately identify and filter spam emails to reduce security risks, protect users, and improve communication efficiency.

## Data Preprocessing, Handling and Analysis
#### 1. Data Cleaning

#### 2. Extrapolatory Data Analysis

#### 3. Text Preprocessing

#### 4. Model Building

#### 5. Model Evaluation

#### 6. Model Improvement and Deployment

## Data Visualization
#### Type Of Data
![image alt](https://github.com/SundeepChaluvadi/Email-Spam-Classifier/blob/0549ae22894d620ff470104b36c29773be1f9e34/Images/TypeOfData.png)

#### Histogram Of Characters for both 0 and 1
![image alt](https://github.com/SundeepChaluvadi/Email-Spam-Classifier/blob/0549ae22894d620ff470104b36c29773be1f9e34/Images/NumOfCharacters_Count.png)

#### Histogram Of Words for both 0 and 1
![image alt](https://github.com/SundeepChaluvadi/Email-Spam-Classifier/blob/0549ae22894d620ff470104b36c29773be1f9e34/Images/NumOfWords_Count.png)

#### Pairplot of Characters, Words and Sentences
![image alt](https://github.com/SundeepChaluvadi/Email-Spam-Classifier/blob/0549ae22894d620ff470104b36c29773be1f9e34/Images/Pairplot_of_Chars_Words_Sentences.png)

#### Heatmap
![image alt](https://github.com/SundeepChaluvadi/Email-Spam-Classifier/blob/0549ae22894d620ff470104b36c29773be1f9e34/Images/Heatmap.png)

#### WordCloud of Spam (1)
![image alt](https://github.com/SundeepChaluvadi/Email-Spam-Classifier/blob/0549ae22894d620ff470104b36c29773be1f9e34/Images/Wordcloud.png)

#### WordCloud of Ham (0)
![image alt](https://github.com/SundeepChaluvadi/Email-Spam-Classifier/blob/0549ae22894d620ff470104b36c29773be1f9e34/Images/Wordcloud_ham.png)

#### Collections of Spam (1)
![image alt](https://github.com/SundeepChaluvadi/Email-Spam-Classifier/blob/0549ae22894d620ff470104b36c29773be1f9e34/Images/Collections.png)

#### Collections of Ham (0)
![image alt](https://github.com/SundeepChaluvadi/Email-Spam-Classifier/blob/0549ae22894d620ff470104b36c29773be1f9e34/Images/Collections_Ham.png)


## Dependencies
```bash
  pip install -r requirements.txt
```

## Demo
https://email-spam-classifier-12345.streamlit.app/

## Installation
Clone the repository:

```bash
  git clone https://github.com/SundeepChaluvadi/Email-Spam-Classifier.git
  cd Email-Spam-Classifier
```

## Model Evaluation
#### Email Spam Classifier Performance
Extra Trees Classifier (ETC): Highest accuracy 97.78%, precision 99.15% – best overall performance. <br>
Random Forest (RF): Accuracy 97.00%, precision 99.08% – strong ensemble model. <br>
SVC: Accuracy 97.29%, precision 97.41% – effective for balanced performance. <br>
XGBoost (XGB): Accuracy 97.20%, precision 95.04% – high-performing gradient boosting model. <br>
AdaBoost: Accuracy 96.23%, precision 95.41% – reliable boosting approach. <br>
Naive Bayes (NB): Accuracy 95.94%, precision 100% – simple but precise model. <br>
Logistic Regression (LR): Accuracy 95.16%, precision 94.00% – solid linear model. <br>
Gradient Boosted Decision Trees (GBDT): Accuracy 95.16%, precision 93.14% – good ensemble option. <br>
Bagging Classifier (BgC): Accuracy 95.74%, precision 86.15% – moderate performance. <br>
Decision Tree (DT): Accuracy 93.52%, precision 83.81% – least effective among tested models. <br>
K-Nearest Neighbors (KN): Accuracy 90.04%, precision 100% – simple but high precision. <br>

![image alt](https://github.com/SundeepChaluvadi/Email-Spam-Classifier/blob/0549ae22894d620ff470104b36c29773be1f9e34/Images/Performance_Analysis.png)


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)]([https://www.linkedin.com/](https://www.linkedin.com/in/sundeep-chaluvadi))

## Sources
https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset
