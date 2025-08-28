# 🎬 Netflix Movies & TV Shows Data Analysis

This project explores the **Netflix dataset** to analyze trends in movies and TV shows, perform data cleaning, manipulation, and build a simple **machine learning model** to classify whether a record is a Movie or TV Show.

---

## 📂 Dataset
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

## 📊 Data Analysis & Manipulation
- Handled missing values (`dropna` for important columns).
- Converted `duration` (Movies → minutes, TV Shows → seasons).
- Encoded categorical features (`LabelEncoder`).
- Extracted insights on:
  - Movies vs TV Shows count
  - Distribution by country
  - Popular release years

---

## 🤖 Machine Learning Model
- **Model Used**: Logistic Regression  
- **Features**: `release_year`, `country`, `duration`  
- **Target**: `type` (Movie = 0, TV Show = 1)  
- **Accuracy Achieved**: ~ *74.38%*  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/swathi-gurijala/netflix-analysis.git
   cd netflix-analysis

