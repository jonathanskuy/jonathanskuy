# Hi there, I'm Jonathan 👋
🧑‍💻 Data Scientist focused on supporting decision-making and building solutions using data, and continuously improving<br>
🎓 BSc(Hons) Data Science and Artificial Intelligence graduate<br>

## Tech Stack 💻
### Data
Python (Pandas, NumPy), Data Wrangling, Exploratory Data Analysis (EDA), Feature Engineering, Geospatial Data (GeoPandas, LSOA/MSOA Boundaries), Relational (Oracle SQL, MySQL) and NoSQL Databases (MongoDB, TinyDB), PySpark, Hadoop, Power BI
### Statistics
Statistical Modelling, Linear Regression, Hypothesis Testing, Regression Assumptions and Diagnostics, Model Comparison Statistics (Akaike Information Criterion)
### AI & Machine Learning
Scikit-Learn, Supervised Learning (Regression, Classification), Deep Learning (Neural Networks, LSTMs, TensorFlow, PyTorch), Gradient-Boosting Algorithms (XGBoost, LightGBM, CatBoost), NLP (BERT fine-tuning, BERTopic)
### MLOps & Deployment
FastAPI, Docker, Google Cloud Run, MLflow, GitHub Actions, Model Versioning, Automated Retraining, Gradio

## Featured Projects 🌟
### Real-Time Transaction Fraud Detection API
**End-to-end MLOps pipeline for detecting fraudulent transactions, served via a production-ready REST API.**

**Key Features**
- Trained an XGBoost classifier model on 911K+ IEEE-CIS transaction records enriched with comprehensive feature engineering, effectively achieving an AUC-ROC of 0.9675 on test data
- Applied threshold tuning to optimise the precision-recall trade-off and achieved an F1 score of 0.7491 (+25% uplift from the baseline model), as well as SHAP explainability to outline interpretable fraud signals
- Packaging the trained model into a FastAPI inference service with Docker, targeting deployment on Google Cloud Run with a GitHub Actions CI/CD pipeline

**Repo:** [Real-Time Transaction Fraud Detection API](https://github.com/jonathanskuy/fraud-detection-api)

### Exploring the Relationship between Education Quality and Property Prices in Manchester
**Quantitative analysis of the relationship between school quality scores and property prices across Manchester.**

**Key Features**
- Integrated 1M+ UK property transaction data records with Ofsted school inspection scores and Index of Multiple Deprivation datasets to analyse their relationship using multiple linear regression 
- Discovered that education quality’s relationship with property prices is statistically significant (p < 0.01) while school access’ relationship holds less significance (p ≈ 0.352)
- Investigated possible links with socioeconomic deprivation and access to amenities, observing that they also reflect property price variation significantly (p < 0.01)
- Produced 10+ spatial visualisations and regression diagnostics to visualise variations and support results and investment insights

**Repo:** [Exploring the Relationship between Education Quality and Property Prices in Manchester](https://github.com/jonathanskuy/manchester-property-vs-education)

### London Property Price Prediction
**End-to-end machine learning pipeline for predicting property prices across London, built as a collaborative group project.**

**Key Features**
- Engineered a production-ready data pipeline processing 100,000+ London property transaction records, enriching each with geospatial coordinates via the ONS Postcode Directory dataset and filtering to 2024 transactions for recency and relevance
- Trained and tuned a CatBoost regression model across 1,000 iterations, improving R² from 0.840 to 0.844 and reducing MAE from 0.175 to 0.172 over the baseline, delivering robust price predictions across diverse property characteristics and external variables
- Deployed an interactive Gradio web application into a HuggingFace Space, enabling users to generate real-time property price estimates from customisable inputs
- Collaborated in a team of 6 with structured roles spanning data preprocessing, modelling, and evaluation; personally led feature engineering and model implementation while contributing significantly to the data preprocessing pipeline

**Repo:** [London Property Price Prediction](https://github.com/jonathanskuy/london-property-price-prediction)

**Interactive Application:** [London Property Price Predictor](https://huggingface.co/spaces/jonathanskuy/london-property-price-predictor)

### Aircraft Engine Predictive Maintenance
**AI-powered system focused on the prediction of aircraft engine maintenance points based on remaining useful life**

**Key Features**
- Developed a complete preprocessing pipeline from raw engine sensor data and engineered temporal features 
such as rolling statistics and trends to capture engine degradation 
- Compared the usage of XGBoost and Ridge regression for the predictive model in terms of the accuracy of engine 
maintenance point prediction 
- Demonstrated that linear models (Ridge) are adequate for simple operating conditions (FD001) while XGBoost 
strongly outperforms it for complex operating conditions (FD004) 
- Achieved approximately 26% decrease in final-cycle MAE on FD004 using XGBoost compared to Ridge regression, 
significantly increasing the accuracy of the predictive model in estimating maintenance points of engines under 
complex operating conditions

**Repo:** [Aircraft Engine Predictive Maintenance](https://github.com/jonathanskuy/aircraft-predictive-maintenance)

## Connect with Me
- **Email:** jonathanindarto1001@gmail.com
- **LinkedIn:** [Marcellinus Jonathan Evanda](https://linkedin.com/in/m-jonathan-indarto)

**Languages:** EN🇬🇧/ID🇮🇩/NL🇳🇱

[![Jonathan's GitHub stats](https://github-readme-stats.vercel.app/api?username=jonathanskuy&count_private=true&show_icons=true&theme=radical&hide_rank=false)](https://github.com/anuraghazra/github-readme-stats)
