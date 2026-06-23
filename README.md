<div align="center">

# 🏦 Bank Marketing Subscription Prediction

### Predicting whether a customer will subscribe to a term deposit using Machine Learning

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=2500&pause=800&color=2F80ED&center=true&vCenter=true&width=850&lines=Bank+Marketing+Classification+Project;Data+Cleaning+%7C+EDA+%7C+Preprocessing+%7C+Logistic+Regression;Customer+Subscription+Prediction+Using+Machine+Learning" alt="Typing SVG" />

</div>

---

## 📌 Project Overview

This project analyzes a **Bank Marketing dataset** to predict whether a customer will subscribe to a **term deposit** based on demographic, financial, and campaign-related information.

The main objective is to build a clean and professional machine learning pipeline that can classify customers into two groups:

- `1` → Customer subscribed to a term deposit  
- `0` → Customer did not subscribe  

This project demonstrates important machine learning concepts such as **data cleaning, handling categorical variables, feature scaling, train-test split, model building, and classification evaluation**.

---

## 🎯 Business Problem

Banks often run marketing campaigns to encourage customers to subscribe to term deposits. However, contacting every customer is expensive and time-consuming.

This project helps answer the question:

> **Can we predict which customers are more likely to subscribe to a term deposit?**

By using machine learning, banks can better target high-potential customers and improve marketing efficiency.

---

## 📂 Dataset Information

The dataset contains customer and campaign-related information from a bank marketing campaign.

### Key Features

| Feature | Description |
|---|---|
| `age` | Customer age |
| `job` | Type of job |
| `marital` | Marital status |
| `education` | Education level |
| `default` | Whether the customer has credit in default |
| `balance` | Average yearly account balance |
| `housing` | Whether the customer has a housing loan |
| `loan` | Whether the customer has a personal loan |
| `contact` | Contact communication type |
| `day` | Last contact day of the month |
| `month` | Last contact month |
| `campaign` | Number of contacts during this campaign |
| `pdays` | Days passed after previous campaign contact |
| `previous` | Number of previous contacts |
| `poutcome` | Outcome of previous campaign |
| `y` | Target variable: term deposit subscription |

---

## 🧠 Machine Learning Workflow

```mermaid
flowchart LR
    A[Load Dataset] --> B[Explore Data]
    B --> C[Check Missing Values]
    C --> D[Remove Duplicates]
    D --> E[Drop Duration Column]
    E --> F[Handle Unknown Values]
    F --> G[Encode Categorical Features]
    G --> H[Scale Numerical Features]
    H --> I[Train-Test Split]
    I --> J[Logistic Regression Model]
    J --> K[Evaluate Model]
