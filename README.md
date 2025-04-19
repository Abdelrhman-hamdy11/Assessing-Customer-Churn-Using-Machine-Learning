# 📱 Telecom Customer Churn Prediction

![image](https://github.com/user-attachments/assets/f7750df0-bbac-457c-bca1-1703900b9f60)


This project focuses on predicting customer churn in the Indian telecom sector by analyzing demographic and usage data. Using machine learning, we aim to identify key factors influencing customer behavior, helping telecom companies enhance their service quality and reduce churn rates.

---

## 📊 Project Overview

The Indian telecom sector is highly competitive, with customers often switching between service providers. Understanding the factors contributing to customer churn is crucial for businesses to retain customers and improve their services. In this project, we use two comprehensive datasets from major telecom companies — Airtel, Reliance Jio, Vodafone, and BSNL — to predict customer churn.

- **Telecom Demographics Data** provides insights into the customer's background, such as age, gender, location, and salary.
- **Telecom Usage Data** includes customer activity metrics such as call frequency, SMS usage, and data consumption.

By analyzing these datasets, the goal is to develop a predictive model that can identify customers who are likely to churn, allowing telecom companies to take preemptive actions to retain them.

---

## 🧹 Data Cleaning and Preprocessing

The project involves cleaning and preprocessing the following datasets:

### 📁 `telecom_demographics.csv`
| Column                | Type       | Description                                           |
|-----------------------|------------|-------------------------------------------------------|
| `customer_id`         | Integer    | Unique identifier for each customer.                 |
| `telecom_partner`     | Categorical| Telecom provider (Airtel, Jio, Vodafone, BSNL).       |
| `gender`              | Categorical| Customer's gender.                                   |
| `age`                 | Integer    | Customer's age.                                      |
| `state`               | Categorical| Customer's state of residence in India.              |
| `city`                | Categorical| Customer's city of residence.                        |
| `pincode`             | Integer    | Customer's location pincode.                         |
| `registration_event`  | Date       | Date when the customer registered.                   |
| `num_dependents`      | Integer    | Number of dependents the customer has.               |
| `estimated_salary`    | Float      | Customer's estimated salary.                         |

### 📁 `telecom_usage.csv`
| Column              | Type       | Description                                           |
|---------------------|------------|-------------------------------------------------------|
| `customer_id`       | Integer    | Unique identifier for each customer.                 |
| `calls_made`        | Integer    | Number of calls made by the customer.                |
| `sms_sent`          | Integer    | Number of SMS messages sent by the customer.         |
| `data_used`         | Float      | Amount of data used by the customer (in MB or GB).   |
| `churn`             | Integer    | Binary variable indicating if the customer churned (1 = churned, 0 = not churned). |

---

## 🔍 Model Building

Using the cleaned data, a machine learning model (e.g., logistic regression, decision tree, or random forest) will be trained to predict customer churn based on the demographic and usage patterns. The model will help telecom companies identify at-risk customers, enabling them to take appropriate retention measures.

---

## 🧑‍💼 Author

**Abdelrhman Hamdy**  
[LinkedIn Profile](https://www.linkedin.com/in/abdelrahman-hamdii/)
