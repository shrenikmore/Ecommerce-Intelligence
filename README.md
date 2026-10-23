# Ecommerce Intelligence 📊

### End-to-End E-commerce Analytics & Machine Learning Project

## 📌 Overview
Ecommerce Intelligence is a data analytics and machine learning project focused on understanding e-commerce performance and predicting order cancellations.

## 🎯 Project Objectives
- Analyze order, customer, product, payment, delivery, return, and marketing data.
- Clean and prepare data using SQL and Python.
- Build interactive dashboards in Power BI.
- Explore machine learning models for order cancellation classification.
- Evaluate model performance and understand classification trade-offs.

## 🛠️ Tools & Technologies
- **SQL / MySQL** — Data querying and analysis
- **Python** — Data processing and analysis
- **Pandas & NumPy** — Data manipulation
- **Scikit-learn** — Machine learning
- **Jupyter Notebook** — Experimentation and documentation
- **Power BI** — Interactive dashboard and business insights

## 🔄 Project Workflow
1. Data cleaning and SQL analysis
2. Exploratory data analysis (EDA)
3. Feature engineering
4. Order cancellation classification
5. Model evaluation and threshold experimentation
6. Power BI dashboard development

## 🤖 Machine Learning
The project explores Logistic Regression and Random Forest to classify cancelled orders.

Observed results at a 0.5 threshold:
- **Logistic Regression:** Accuracy 50.6%; cancellation recall 49.4%
- **Random Forest:** Accuracy 72.0%; cancellation recall 17.0%

Threshold experimentation with Logistic Regression achieved 100% cancellation recall at a 0.3 threshold, with cancellation precision of approximately 16.7%.

These results highlight the trade-off between identifying cancelled orders and generating false alarms. Further tuning and validation are needed before practical deployment.

## 📁 Project Files
- `Ecommerce-Intelligence-Dashboard.pbix` — Power BI dashboard
- `Ecommerce-Intelligence-Data-Science.ipynb` — Data science notebook
- `cancellation_model_results.csv` — Model evaluation results

## ⚠️ Limitations & Future Improvements
- Improve cancellation prediction using additional features and model tuning.
- Evaluate performance with cross-validation and suitable classification metrics.
- Investigate class imbalance and threshold selection.
- Add deployment and monitoring if the model becomes reliable enough.

## 👨‍💻 Author
**Shrenik More**

Data Analytics | Data Science | Machine Learning | Power BI
