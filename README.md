
# 🛒 Product-Recommendation-System-Amazon-

A Machine Learning-based Recommendation System that predicts user preferences and suggests products using Collaborative Filtering techniques. The project leverages the Amazon Product Reviews dataset and implements the Singular Value Decomposition (SVD) algorithm to generate personalized product recommendations.

---

## 📌 Overview

Recommendation systems are a core component of modern e-commerce platforms such as Amazon, Netflix, and Spotify. This project demonstrates how machine learning can be used to analyze user-product interactions and predict ratings for unseen products.

Using historical review data, the system learns latent user and product features and recommends products that a user is likely to rate highly.

---

## 🎯 Objectives

* Build a personalized recommendation engine.
* Analyze Amazon product review data.
* Implement Collaborative Filtering using Matrix Factorization.
* Predict user-product ratings.
* Generate personalized product recommendations.
* Evaluate recommendation performance using RMSE.

---

## 🚀 Features

✅ Data preprocessing and cleaning

✅ Exploratory Data Analysis (EDA)

✅ Rating distribution analysis

✅ Top-reviewed product analysis

✅ Collaborative Filtering

✅ Matrix Factorization using SVD

✅ User-specific product recommendations

✅ Model evaluation using RMSE

✅ Scalable recommendation pipeline

---

## 🧠 Machine Learning Approach

The recommendation engine is based on **Collaborative Filtering**, which identifies patterns in user behavior and predicts future preferences.

### Algorithm Used

### Singular Value Decomposition (SVD)

SVD decomposes the user-item interaction matrix into latent factors representing:

* User preferences
* Product characteristics
* Hidden relationships between users and products

This approach is widely used in industrial recommendation systems due to its effectiveness and scalability.

---

## 📊 Dataset

### Amazon Product Reviews Dataset

The dataset contains:

* User IDs
* Product IDs
* Product Ratings

### Sample Features

| Feature   | Description                |
| --------- | -------------------------- |
| UserId    | Unique customer identifier |
| ProductId | Unique product identifier  |
| Score     | Product rating (1–5)       |

---

## 🛠️ Tech Stack

### Programming Language

* Python

### Data Processing

* Pandas
* NumPy

### Visualization

* Matplotlib
* Seaborn

### Machine Learning

* Scikit-Surprise
* SVD Algorithm

### Dataset Source

* KaggleHub
* Amazon Product Reviews Dataset

### Development Environment

* Jupyter Notebook

---

## 📂 Project Structure

```text
amazon-product-recommendation-system/
│
├── Data/
│   └── How to get dataset.docx
│
├── Images/
│   └── Rating Distribution.png
│
├── Notebooks/
│   └── AMAZON_PRODUCT_RECOMMENDATION.ipynb
│
├── requirements.txt
└── README.md
```

---

## 🔄 Project Workflow

### 1. Data Collection

* Download Amazon Product Reviews dataset from Kaggle.
* (
https://www.kaggle.com/datasets/arhamrumi/amazon-product-reviews
)

### 2. Data Preprocessing

* Select relevant columns
* Handle missing values
* Rename columns
* Sample data for efficient training

### 3. Exploratory Data Analysis

* Rating distribution
* Most reviewed products
* User-product interaction analysis

### 4. Model Development

* Prepare data using Surprise Dataset API
* Train-test split
* Train SVD recommendation model

### 5. Evaluation

* Generate predictions
* Compute RMSE
* Analyze recommendation quality

### 6. Recommendation Generation

* Predict user ratings for products
* Recommend products with highest predicted scores

---

## 📈 Results

The model successfully learns user-product interaction patterns and predicts ratings for unseen products.

### Key Outcomes

* Personalized recommendations
* Reduced information overload
* Improved user experience
* Potential increase in customer engagement and sales

---

## 📉 Evaluation Metric

### Root Mean Square Error (RMSE)

RMSE measures the difference between actual and predicted ratings.

Lower RMSE indicates better recommendation performance.

---

## 💡 Business Impact

This recommendation system can help e-commerce platforms:

* Increase customer retention
* Improve product discoverability
* Boost conversion rates
* Enable personalized shopping experiences
* Increase cross-selling opportunities
* Enhance customer satisfaction

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/abhinav8002/amazon-product-recommendation-system.git
cd amazon-product-recommendation-system
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Notebook

```bash
jupyter notebook
```

Open:

```text
Notebooks/AMAZON_PRODUCT_RECOMMENDATION.ipynb
```

---

## 📚 Concepts Covered

### Machine Learning

* Recommendation Systems
* Collaborative Filtering
* Matrix Factorization
* Model Evaluation

### Data Science

* Data Cleaning
* Exploratory Data Analysis
* Statistical Analysis
* Data Visualization

### Recommender Systems

* User-Based Recommendations
* Product-Based Recommendations
* Rating Prediction
* Personalization


## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

* Recommendation Systems
* Collaborative Filtering
* Matrix Factorization
* SVD Algorithm
* Machine Learning Pipelines
* Data Analysis
* Model Evaluation
* Personalized Recommendation Engines

---

## 👨‍💻 Author

### Abhinav Kumar

Machine Learning • Deep Learning • NLP • Generative AI

🔗 GitHub: https://github.com/abhinav8002/Product-Recommendation-System-Amazon-

Open to collaborations in:

* Machine Learning
* Recommendation Systems
* Deep Learning
* NLP
* Generative AI

⭐ If you found this project useful, consider giving it a star.

---

## 📖 References

1. Amazon Product Reviews Dataset(
https://www.kaggle.com/datasets/arhamrumi/amazon-product-reviews)

2. Scikit-Surprise Documentation
3. KaggleHub Documentation
4. Recommendation Systems Handbook
5. Matrix Factorization Techniques for Recommender Systems
