# Dafne Ramírez 👋
## Business Intelligence & Automation Analyst
**I build scalable data systems that drive measurable business impact.**

## Impact Highlights
* +60% campaign revenue growth
* 83% reporting time reduction
* 97% data error reduction
* 63% operational efficiency improvement

## 🛠️ Tech Stack visual
* Power BI
* SQL
* Python (Pandas, Sklearn)
* ETL
* Machine Learning
* Power Platform
* English (B1)

## Sales Forecasting Demand Optimization

#### Business Problem
Reckitt needed to understand product consumption patterns and improve demand planning accuracy. The challenge was to consolidate sales data, segment products based on performance behavior, and forecast future demand to support strategic inventory and marketing decisions.

#### Dataset
Historical sales and consumption data processed through ELT pipelines using SQLite, including transactional records, product-level performance metrics, and time-series sales data for forecasting analysis.

#### Methodology
I designed an ELT workflow to clean and structure the data, performed exploratory data analysis (EDA) to identify trends and seasonality, implemented clustering techniques for product segmentation, and built ARIMA/SARIMA time-series models to forecast sales. The results were visualized through interactive dashboards in Python and Power BI for executive decision-making.

#### Results
The project identified high-performing product clusters, uncovered seasonality patterns, and generated multi-year sales forecasts (extended to 2024–2026). The solution demonstrated how predictive analytics can optimize demand planning and reduce uncertainty in inventory strategy.

#### Screenshots
Include:
* Power BI executive dashboard overview
* mTime-series forecast visualization (ARIMA/SARIMA output)
* Product clustering visualization (scatter plot or PCA projection)
* [Reckitt - Sales Prediction with Machine Learning](https://github.com/databimx/databimx/blob/790f6e9281df393c92fc628343cc31a45e8fcc7a/Reckitt.jpg)

#### What I Would Do Differently in Production
In a production environment, I would deploy the forecasting model using a cloud-based pipeline (BigQuery or Snowflake), automate retraining schedules, implement model performance monitoring (MAPE tracking), and integrate the dashboard directly into a live data warehouse to ensure real-time decision support.

## NLP Sentiment Analytics
#### Business Problem
Understanding user sentiment at scale is critical for app positioning and pricing strategy. The objective was to analyze app categories, ratings, pricing models, and user reviews to extract actionable insights that could inform product strategy and monetization decisions.

#### Dataset
Google Play Store dataset containing app categories, ratings, pricing, size, and thousands of user reviews in unstructured text format.

#### Methodology
Performed data cleaning and feature engineering, followed by exploratory analysis to identify relationships between category, pricing, and ratings. Implemented Natural Language Processing (NLP) techniques to classify review sentiment (positive, negative, neutral). Combined structured and unstructured analysis to generate actionable KPIs.

#### Results
The analysis revealed that free and lightweight apps dominate downloads, with an average rating of 4.3 across categories. Sentiment analysis showed predominantly positive feedback, with price playing a more significant role in adoption than category alone. The project demonstrates how NLP can transform unstructured reviews into strategic product insights.

#### Screenshots
Include:
* Sentiment distribution bar chart
* Category vs Rating visualization
* Free vs Paid comparison
* [Google - Conclusions 1](https://github.com/databimx/databimx/blob/790f6e9281df393c92fc628343cc31a45e8fcc7a/Google.jpg)

#### What I Would Do Differently in Production
In production, I would deploy a transformer-based NLP model (e.g., BERT), implement real-time sentiment streaming using APIs, and create an automated alert system to flag sudden negative sentiment spikes affecting app ratings.


## Customer Segmentation Recommendation Engine
#### Business Problem
E-commerce platforms rely on personalization to increase retention and conversion rates. The goal of this project was to segment customers based on behavioral patterns and generate product recommendations using clustering techniques.

#### Dataset
Amazon customer purchase dataset including product attributes, ratings, delivery preferences, durability scores, and customer-level interaction metrics.

#### Methodology
Performed preprocessing and dimensionality reduction using PCA, followed by hierarchical clustering to group customers with similar preferences. Analyzed cluster characteristics to design recommendation logic based on shared behavioral attributes.

#### Results
Identified distinct behavioral clusters driven by delivery speed, product quality, durability, and visual presentation preferences. Generated personalized recommendation logic based on similarity patterns, demonstrating how segmentation can support targeted marketing and increase purchase probability.

#### Screenshots
Include:
* Dendrogram (Hierarchical Clustering)
* PCA 2D visualization
* Example of customer-to-customer recommendation mapping
* [Amazon - PCA](https://github.com/databimx/databimx/blob/790f6e9281df393c92fc628343cc31a45e8fcc7a/Amazon.jpg)

#### What I Would Do Differently in Production
In a real-world implementation, I would transition from clustering-based similarity to a hybrid recommendation engine (collaborative + content-based filtering), deploy it via API, and evaluate performance using precision@k and recall@k metrics within an A/B testing framework.


## 📫 Contacto
* **LinkedIn:** www.linkedin.com/in/daph-data-1257ab356
* **Email:** data.bi.mx@gmail.com
* **Ubicación:** Ciudad de México
* **WEB Portfolio:** https://sites.google.com/view/dafolio/home

## License
All the projects presented here are part of my personal portfolio. 

---
<!--
