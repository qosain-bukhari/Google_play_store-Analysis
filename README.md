# Create the README.md file content
readme_content = """
# 📱 Google Play Store App Analysis

📊 Exploratory Data Analysis on real-world app data from Google Play Store

---

## 📁 Dataset Information

- **Source:** [Kaggle - Google Play Store Dataset](https://www.kaggle.com/datasets/lava18/google-play-store-apps)
- **Total Apps:** ~10,000
- **Columns:** App, Category, Rating, Reviews, Size, Installs, Type, Price, Content Rating, etc.

---

## 🚀 Project Objectives

- Clean and preprocess messy real-world data
- Analyze patterns across app categories
- Visualize ratings, installs, price, and reviews
- Discover top apps per category
- Practice Python, Pandas, and Seaborn for EDA
- Build a GitHub portfolio project

---

## 🔍 Exploratory Data Analysis (EDA)

### 🧼 Data Cleaning:
- Removed missing/null values
- Converted columns like `Size`, `Price`, `Installs` into usable numeric formats
- Cleaned special characters: `$`, `+`, `Free`, `,`

### 📊 Univariate Analysis:
- Distribution of Ratings, Reviews, Installs, Price
- Top Categories by app count
- Most common Content Ratings
- Free vs Paid apps analysis

### 📈 Bivariate Analysis:
- Top 5 installed apps in each popular category
- Category-wise rating and install relationships
- Correlation between numerical features

---

## 📸 Visualizations

- KDE plots for numeric features (Rating, Reviews, Size, Price)
- Count plots for categorical features (Type, Content Rating)
- Bar charts: Top Categories by App Count
- Grouped bar charts: Top Installed Apps per Category
- Correlation heatmap

---

## 📈 Key Insights

- Most apps on the store are **Free (~90%)**
- **Family** and **Game** are the top categories
- Ratings are mostly between **4.0 and 4.5**
- A few apps dominate installs (e.g., 1B+), many apps have very low installs
- Most apps are suitable for **Everyone**

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook
- Git & GitHub for version control

---

## 🧠 What I Learned

- Handling real-world messy data
- Transforming categorical and numerical columns
- Building visual stories using Seaborn and Matplotlib
- Improving GitHub profile with real data projects
- Sharpening my EDA and data storytelling skills

---

## 💡 Future Work

- Build a machine learning model to predict app rating or success
- Use NLP to analyze user reviews
- Deploy insights in a Streamlit dashboard

---

## 📂 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/qosain-bukhari/Google_play_store-Analysis.git
