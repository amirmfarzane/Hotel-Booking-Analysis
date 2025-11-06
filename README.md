# 🏨 Booking.com Hotel Pricing Analysis

## 📌 Overview
This project presents a comprehensive analysis of hotel pricing patterns on **Booking.com**, completed as part of the **Foundations of Data Science** course at the **University of Tehran**.  
The workflow includes **web scraping**, **feature engineering**, **exploratory data analysis (EDA)**, and **machine learning model development** to understand price drivers and build predictive models.

## 📂 Table of Contents
1. [🧭 Data Scraping](#-data-scraping)
2. [🔧 Feature Engineering & EDA](#-feature-engineering--eda)
3. [🤖 Model Training](#-model-training)
4. [📊 Results](#-results)
5. [✅ Conclusion](#-conclusion)
6. [📄 License](#-license)

---

## 🧭 Data Scraping
Hotel data was collected directly from **Booking.com** using Python and **BeautifulSoup**.

Key tasks:
- Extracted attributes such as **price**, **rating**, **location**, **amenities**, and **reviews**.
- Allowed customization for **number of guests** and **stay duration**.
- Supported **multiple cities** by extracting city identifiers from the HTML source.

**Documentation & Code:**
- Description: `P0/DS-Project-P0.pdf`  
- Implementation: `scrap.ipynb`

---

## 🔧 Feature Engineering & EDA
Data preprocessing and analysis included:

- Cleaning, encoding, and normalizing features
- Creating new derived features
- Managing missing values and outliers

Exploratory Data Analysis (EDA):
- Descriptive statistics and distributions
- Correlation and feature importance studies
- Visualizations to highlight pricing patterns and trends

**Documentation & Code:**
- Description: `P1/DS-Project-P1.pdf`  
- Implementation: `P1/DS-Project-P1.ipynb`

---

## 🤖 Model Training
Multiple regression and tree-based models were trained to predict hotel prices.

Workflow:
- Train/test split
- Model training and hyperparameter tuning
- Evaluation using regression performance metrics

**Documentation & Code:**
- Description: `P2/DS-Project-P2.pdf`
- Implementation: `P2/DS-Project-P2.ipynb`

---

## 📊 Results
Performance of models on the test set:

| Model                     | R² Score |
|--------------------------|---------:|
| ⭐ **XGBoost**            | **0.98** |
| Random Forest Regressor  | 0.94     |
| Neural Network           | 0.90     |
| K-Nearest Neighbors      | 0.84     |
| Polynomial Regression    | 0.79     |
| MLP Regressor            | 0.77     |
| Linear Regression        | 0.57     |

✅ **XGBoost demonstrated the strongest predictive performance.**

---

## ✅ Conclusion
This project successfully applied data science methods to real-world travel marketplace data.  
The analysis revealed key pricing determinants, and the predictive models can support hotel pricing strategies and traveler decision-making.

---

## 📄 License
This project is released under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.
