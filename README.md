# 🎈🎈Data Mining Fianl Project 2021 Summer

👱‍♀️Yuqing Liu(YL110057)

## 📚algorithm

* LogisticRegression
* Descision tree
* Bagging

## 📈Dataset https://www.kaggle.com/shivamb/real-or-fake-fake-jobposting-prediction

# 1. Introduction
## 1.1  Motivation
In the past few years, people have used intuition to distinguish fake job postings. For example, unusually high salaries may suggest false job postings. Nowadays, big data technology allows us to process these usage models to release job data more reliably and identify fake data. The goal of our project is to train a classifier to identify fake or real job postings using functions such as salary range, benefits, Required_experience, Required_education, etc.

## 1.2  Dataset Description
This dataset contains 18K job descriptions out of which about 800 are fake. The data consists of both textual information and meta-information about the jobs. The dataset can be used to create classification models which can learn the job descriptions which are fraudulent.

## 1.3  Description of Task
Our task is to bulid some models to predict whether the job is fake or not.

## 1.4  Descripe Target Variables
fraudulent - the job is fake or not? (binary: 'yes', 'no')
## 1.5  Features Explanation
### 1.5.1  Variables
![image](https://user-images.githubusercontent.com/69694512/119100868-f96dc900-ba4a-11eb-9668-665f2c55fd21.png)
### 1.5.2  Output variable (desired target):
fraudulent - the job is fake or not? {binary| 'yes':1 , 'no':0}

# 2. Cleaning and Preprocessing Data
* Removing or imputing missing Data
* Handing Outliers

# 3. EDA
## 3.1  Education Related Variables
![image](https://user-images.githubusercontent.com/69694512/119101115-3a65dd80-ba4b-11eb-9f64-8868874846c2.png)
![image](https://user-images.githubusercontent.com/69694512/119101147-418ceb80-ba4b-11eb-8c05-a3bd8244c951.png)

### 3.1.0.1  Real Posts
✅Telecommuting
✅Company Logo
✅Employment Type
✅Required Experience and Education
### 3.1.0.2  Fradulent Posts
❌Telecommuting
❌Company Logo
✅Employment Type
✅Required Experience and Education

## 3.2  Text information variables
![image](https://user-images.githubusercontent.com/69694512/119101249-5b2e3300-ba4b-11eb-89e5-0430f80e3b90.png)
![image](https://user-images.githubusercontent.com/69694512/119101265-5f5a5080-ba4b-11eb-9df8-96dc72aad636.png)
### 3.2.1  Real Posts
✅
### 3.2.2  Fradulent Posts
✅
# 4. Data Processing
## 4.1  Key-value
## 4.2  One hot encode
## 4.3  PCA
## 4.4  StandardScale
## 4.5  Dealing with data imbalance by upsampling
## 4.6  Clone
## 4.7  Feature Selection
# 5.  Bulid the model
## 5.1  PCA_LR
## 5.2  PCA_ Decision Tree
## 5.3  Bagging
##########
* LR | 0.447
* DT | 0.879
* BA | 0.961





