# 🎬 Netflix Movies & TV Shows Data Analysis
Data Analysis and Machine Learning on Netflix Movies & TV Shows Dataset.
This project explores the **Netflix dataset** to analyze trends in movies and TV shows, perform data cleaning, manipulation, and build a simple **machine learning model** to classify whether a record is a Movie or TV Show.

---

## 📊 About the Dataset

- **Source:** [Netflix Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
The dataset contains:
- `show_id`
- `type`
- `title`
- `director`
- `cast`
- `country`
- `date_added`
- `release_year`
- `rating`
- `duration`
- `listed_in`
- `description`

---

## 🛠️ Tools & Libraries Used
- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib & Seaborn**
- **Scikit-learn**

---

## 🧹 Data Cleaning
- Handled missing values  
- Dropped unnecessary columns  
- Checked and removed duplicates  
- Converted `date_added` to datetime format  

---
## 🔍 Exploratory Data Analysis (EDA)
- Distribution of Movies vs TV Shows  
- Most common countries producing content  
- Trend of releases over the years  
- Popular genres and ratings  

---
## ⚙️ Feature Engineering
- Extracted `year_added`, `month_added` from `date_added`  
- Processed categorical features for ML  

---

## 🤖 Machine Learning Model
- **Model Used**: Logistic Regression  
- **Features**: `release_year`, `country`, `duration`  
- **Target**: `type` (Movie = 0, TV Show = 1)  
- **Accuracy Achieved**: ~ *74.4%*  

---

## 🚀 How to Run

1. Clone the repository:
   check my collab file:
   (collab)[https://colab.research.google.com/drive/1VN_yaM7PBw8lMtxERgjnIfc_ASG1ji6B?usp=sharing]

   if you want to clone from my github:
   
   git clone https://github.com/swathi-gurijala/netflix-analysis.git
   cd netflix-analysis

