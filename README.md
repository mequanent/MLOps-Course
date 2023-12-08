# MLOps-Course
MLOps Course – Build Machine Learning Production Grade Projects [From freeCodeCamp, accessed on the 3rd day of its release date. Found by a weekly email from Quincy Larson, Teacher and founder of freeCodeCamp.org]

Link to YouTube Tutorial: https://youtu.be/-dJPoLm_gtE 

# ML Teams - What are the Roles 
<img src="/images/1 ML Teams 2023-12-08 13-42-10.png">

## ML in Production - What we Think it looks like
<img src="/images/2 ML in Production thinking 2023-12-08 13-48-01.png">

## ML in Production - What it actually looks like
<img src="/images/3 ML in Production actual 2023-12-08 13-51-14.png">
<img src="/images/4 ML in Production cycle 2023-12-08 13-55-18.png">

How data affects our model/system.
<img src="/images/5 Data affects model 2023-12-08 20-11-45.png">

That's where MLOps is the rescue. 
<img src="/images/6 MLOps 2023-12-08 20-14-41.png">

Post-deployment woes (woe -> trouble, difficulty, sorrow, distress): 
* Accountinf for latency --> 53% of visits are abandoned if a mobile site takes longer than 3 seconds to load.
* Maintaining fairness --> It will learn bad things until becoming racist. 
* Lack of explainability and audibility
* It's painfully slow.

# Model-centric vs Data-centric
<img src="/images/7 Model-centric vs Data-centric 2023-12-08 20-22-27.png">

# What's the business problem we're trying to solve?
* Cost of wrong predictions --> will cause overstock and understock
  * Breaking down the sales forecasting process -> dcompose the task into component tasks like: data gathering, historical data analysis, market trend analysis, and actual forecasting.
  * Identifying AI/ML Opportunities --> AI/ML could be useful in the actual forecasting task, where it could analyze past sales data and market trends to predict future sales with higher accuracy than traditional methods.
  * Estimating the ROI of AI/ML Implementation --> The ROI could be estimated by comparing the potential increase in sales and decrease in wasted resources due to improved forecasts, against the costs of developing and maintaining the AI/ML solution.
  * Prioritizing Tasks for AI/ML Implementation --> In this case, there's primarily one task that could benefit from AI/ML, which is the actual forecasting. Therefore, we prioritize it for implementaion.
  *  
# Understanding the ML Canvas:
  * The Machine Learning Canvas: a tool with ten blocks that helps us structure and plan our ML application development. It is a framework to connect the dots between data collection, machine learning, and value creation.
## 1. Value Proposition: 
* Defining the problem, its importance, and our end-user persona.
* Geoffrey Moore's Value Positioning Statement Template: For (target customer) who (need), our (product/service) is (product category) that (benefit).
## 2. Data Sources: 
* Identifying potential sources of data, including internal databases, APIs, open datasets, and more.
* Considering hidden costs such as data storage and purchasing external data.
## 3. Prediction Task:
* Deciding the ML task: Supervised or unsupervised? Anomaly detection? Classification, regression, or ranking?
* Thinking about input, output and the degree of model complexity.
## 4. Feature Engineering: 
* Working with domain experts to extract features from raw data sources. 
## 5.Offline Evaluation:
* Setting up metrics to evaluate system performance pre-deployment.
* Understanding model prediction errors and their impacts. 
## 6. Decisions:
* Using predictions to make decisions: how will the end-user interact with our predictions?
* Possible hidden costs, including human intervention
## 7. Collecting Data:
* Collecting new data for model re-training and preventing model decay.
* Cost considerations for data collection and the role of humans in data labeling. 
## 8. Building Models: 
* Deciding frequency of model re-training and associated hidden costs.
* Planning for changes in tech stack and scaling. 
## 9. Live Evaluation & Monitoring:
* Setting up metrics to track system performance post-deployment.
* Understanding the correlation between model metrics and business metrics.
## 10. When not to Implement AI/ML?
* Identifying situations where AI/ML may not be the best solution.

# Workflow of ML-based Software Development
* Three main artifacts in ML-based software: Data, ML Model, and Code.
* Three main phases: Data Engineering, ML Model Engineering, and Code Engineering.
## Data Engineering Introduction: 
* Data acquisition and data preparation
* Most resource and time-consuming phase
* Prevents propagation of data errors to the next phase. 
## Data Engineering Pipeline:
* Data Ingestion: Collection of data from sources
* Exploration and Validation: Understanding data content and structute
* Data Wrangling: Formatting and cleaning data
* Data Labeling: Assigning categories to data points
* Data Splitting: Division of data into training, validation, and testing
## Model Engineering Introduction:  
* Core of ML workflow: writing and executing ML algorithms
* Obtaining the ML model
## Model Engineering Pipeline:
* Model Training: Applying ML algorithms on training data 
* Model Evaluation: Validating the model pre-deployment 
* Model Testing: Final acceptance test using test dataset 
* Model Packaging: Exporting model into a consumable format for business application 

## Model Deployment Introduction:  
* Model Serving: Addressing the ML model in a production environment
* Model Performance Monitoring: observing performance on live, unseen data
* Model Performance Logging: Recording every inference request
## Model Engineering Pipeline:

# We will use ZenML to DEVELOP, EXECUTE & MANAGE 

<img src="/images/8 ZenML Introduction 2023-12-08 21-47-06.png">

Next to Google Colab: https://colab.research.google.com/drive/16gvZ1R6285ycELMHShtbUnR-3CXi5TqI?usp=sharing 
