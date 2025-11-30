# **Leveraging Predictive Analytics and NLP Modelling to Enhance Airline Operations and Customer Loyalty**

### *Integrated Machine Learning and NLP System for Airline Delay Forecasting & Customer Sentiment Intelligence*

---

##  Project Overview

This project delivers a dual-framework machine learning solution designed to enhance airline operations and strengthen customer loyalty.  
By combining **predictive analytics** with **NLP-driven sentiment analysis**, it provides airlines with actionable insights on:

- **Operational Efficiency** – anticipating and reducing flight delays  
- **Customer Experience** – understanding passenger sentiment at scale  

The project demonstrates technical capability in data engineering, predictive modelling, and advanced NLP while addressing real-world industry challenges.

---

## Project Objectives

### 1. Flight Delay Prediction
- Identify and analyze key operational factors influencing delays  
- Build and compare machine learning models to forecast delay likelihood  
- Enable proactive decision-making for scheduling, staffing, and disruption management  

### 2. Customer Sentiment & Loyalty Analysis
- Analyze 14,640+ customer tweets about U.S. airlines  
- Detect sentiment levels, complaint themes, and loyalty risks  
- Support airlines in enhancing communication, service quality, and customer retention  

---

## Datasets
- **Flight Delay & Cancellation Dataset (2019–2023)**  
- **Airline Tweet Dataset** (14,640 labeled tweets with sentiment & complaint categories)

Both datasets underwent cleaning, standardization, feature engineering, and NLP preprocessing (TF-IDF).

---

## Methods & Techniques

### **Machine Learning (Flight Delays)**
- Logistic Regression  
- Random Forest  
- Decision Tree  
- Gradient Boosting (optional)  
- Performance measured via accuracy, recall, and interpretability  

### **NLP & Text Mining (Customer Tweets)**
- Text preprocessing & TF-IDF vectorization  
- Logistic Regression for sentiment classification  
- K-Means clustering to discover customer experience segments  
- Apriori Association Rules for frequent complaint patterns  
- Isolation Forest to identify critical or unusual complaints  

The best-performing classifier: **Logistic Regression** for sentiment prediction.

---

## Key Insights

### **Flight Delay Findings**
- Weather, airline, origin airport, and departure time are strong delay predictors  
- Delay probability follows predictable daily and seasonal patterns  
- ML models provide accurate forecasts that can reduce operational disruptions  

### **Customer Sentiment Findings**
- Over **60% of customer tweets are negative**, indicating widespread dissatisfaction  
- Top complaint themes:
  - Flight delays  
  - Customer service issues  
  - Lost or mishandled luggage  
- Anomalies (~2%) represent high-urgency complaints requiring immediate attention  

---

## Conclusion

This project showcases the power of combining **predictive analytics** and **natural language processing** to deliver full-spectrum insights for the airline industry.  
The integrated approach enables airlines to:

- Reduce delays through data-driven forecasting  
- Improve service quality using real-time customer sentiment  
- Strengthen loyalty by addressing critical issues proactively  

