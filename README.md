# Zomato Rating Prediction and Sentiment Analysis

This project, developed as part of my MSc dissertation, focuses on predicting restaurant ratings and performing sentiment analysis on the Zomato dataset. The project aims to understand factors influencing restaurant ratings and analyze restaurant trends across Bengaluru, India's IT capital.

---

## **Project Overview**

Bengaluru, home to over 12,000 restaurants, presents a thriving market for eateries, with a rapidly growing demand for diverse cuisines. This project delves into:

1. **Rating Prediction**: Identifying and predicting factors influencing Zomato restaurant ratings.
2. **Sentiment Analysis**: Analyzing user reviews to determine sentiment (positive, neutral, or negative) and its effect on ratings.
3. **Exploratory Data Analysis (EDA)**: Visualizing restaurant types, location trends, food preferences, and other demographic insights.

The project leverages machine learning algorithms and data science techniques to provide actionable insights for restaurants to enhance their offerings and competitiveness.

---

## **Project Objectives**

- **Rating Prediction**: Understand the key factors that influence ratings and build models to predict ratings based on restaurant attributes.
- **Sentiment Analysis**: Perform sentiment analysis on user reviews to determine the impact of sentiments on overall ratings.
- **Location-Based Analysis**: Identify location-specific food preferences and restaurant trends in Bengaluru.
- **Provide Insights**: Offer valuable insights for both new and existing restaurants to improve their business strategies.

---

## **Repository Contents**

The repository contains the following files:

- **zomato_12_11.ipynb**: Jupyter Notebook with the entire code for:
  - Data preprocessing
  - Exploratory Data Analysis (EDA)
  - Sentiment analysis and visualizations
  - Machine learning models for rating prediction
- **Model Prediction Sample.csv**: A sample CSV file showing predicted ratings and key features.
- **10969852_CEM7150.pdf**: A detailed 15,000-word dissertation report covering:
  - Abstract
  - Literature review
  - Methodology and machine learning algorithms
  - EDA, results, testing, and conclusions
  - Future work and student reflections
- **README.md**: Project documentation.

---

## **Technologies Used**

- **Programming Language**: Python
- **Libraries**:
  - Data Analysis: `Pandas`, `NumPy`
  - Visualizations: `Matplotlib`, `Seaborn`
  - Machine Learning: `Scikit-learn`
  - Text Analysis: `NLTK`, `TextBlob`
- **Environment**: Jupyter Notebook

---

## **Project Workflow**

1. **Exploratory Data Analysis (EDA)**:
   - Analyzed key features such as cost, location, cuisine type, and ratings.
   - Visualized correlations, trends, and outliers in the data.

2. **Rating Prediction**:
   - Built machine learning models (e.g., Linear Regression, Random Forest) to predict ratings based on features like cost for two, location, cuisine type, and delivery options.

3. **Sentiment Analysis**:
   - Processed user reviews using `TextBlob` and `NLTK` to extract sentiment (positive, negative, or neutral).
   - Analyzed how sentiment influences restaurant ratings.

4. **Results and Insights**:
   - Identified the top factors influencing ratings and user reviews.
   - Provided demographic insights into food preferences, including vegetarian options and location-based preferences.

---

## **Setup Instructions**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Monish-Nallagondalla/Zomato-Rating-prediction-.git
   cd Zomato-Rating-prediction-
   
2. **Install Dependencies**: Install the required libraries using pip:
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn nltk textblob
  ```
3.Run the Jupyter Notebook: Open the notebook zomato_12_11.ipynb in Jupyter Notebook
  
---

## **Key Insights and Results**

Top Influencing Features: Features like the cost for two, location, online delivery options, and restaurant type were found to have a significant impact on ratings.

Sentiment Trends: Restaurants with more positive reviews tended to have higher ratings.

Location-Based Preferences: Certain areas of Bengaluru exhibited strong preferences for specific cuisines and dining styles (e.g., vegetarian options in certain regions).

The predictive models achieved reasonable accuracy in estimating restaurant ratings, and sentiment analysis helped correlate review sentiments with restaurant performance.

---

## **Future Work**
Advanced Sentiment Analysis: Implement deep learning models (e.g., LSTM) for more accurate sentiment analysis.

Deployment: Deploy the rating prediction model as a web service or tool for restaurant businesses.

Expanding the Dataset: Include reviews from other cities to make the analysis more comprehensive.

Real-Time Data: Integrate real-time data to provide up-to-date insights for restaurants.

## **Acknowledgements**
This project was completed as part of my MSc dissertation, and I would like to express my gratitude to my supervisors and colleagues for their valuable support and guidance throughout the process.

---
## **License**
This project is licensed under the MIT License. See the LICENSE file for details.

---

## **Contact**
For any queries or collaboration, feel free to reach out:

Name: Monish Nallagondalla
GitHub: Monish-Nallagondalla
