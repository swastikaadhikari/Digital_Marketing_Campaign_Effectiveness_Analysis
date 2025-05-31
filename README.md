# 📈 Digital Marketing Campaign Analysis
Project Overview:

This project analyzes the efectiveness of digital marketing campaigns data-driven techniques. It aims to identify what drives successful campaigns, evaluate performance across channels and customers. It provides insights into customer demographics, marketing channels, campaign performance.

# Dataset Details:
Customer ID: Distinct identifier assigned to every customer

Age: Age of the customer

Gender: Gender of the customer(Male/Female)

Income: Annual income of the customer

Marketing Metrics

Campaign Channel:Medium used to distribute the marketing campaign(Email, Social Media, SEO, PPC, Referral)

Campaign Type:Type of marketing campaign(Awareness, Consideration, Conversion, Retention)

AdSpend:Amount spend on marketing campaign

ClickThroughRate:Rate at which customers click on marketing content

ConversionRate:Rate at which clicks convert into desired actions(such as : purchases, sign-ups, or downloads)

AdvertisingPlatform:Confidential

AdvertisingTool:Confidential

Customer Engagement Indicators:

Website Visit: Total number of times users have accessed a website

Pages Per Visit: Average number of pages user views during a single session on a website

Time On Site: Average time spent on the website per visit(minutes)

Social Shares:Number of time marketing content was shared on social sites

Email Opens: Number of marketing emails were opened

Email Clicks: Number of times links in marketing emails were clicked

Historical Data:

Previous Purchases:The total number of times a customer has made a purchases on past this helps to understand customer behaviour

Loyalty Points: Number of loyalty points accumulated by customer

Target Variable:

Conversion: Binary variable that indicates whether a customer has completed a desired action
            Converted(1): The customer successfully completed the intended action.
            Not Converted(0): The customer didnot take desired action

## 🧾 Project Summary
The objective of this project is to:
- Clean and prepare data
- Analyze performance metrics(CTR,converion rate)
- Visualize campaign effectiveness
- Identify success patterns
- Generate marketing recommendations

## Tools used
VS Code: Data Cleaning, exploratory data analysis (EDA)
Pandas: Data manipulation and preprocessing
Matplotlib and Seaborn: Data Visualization

## 📂 Project Structure

├── digital_marketing_campaign_dataset.csv # Input dataset
├── Marketing_Campaign_.ipynb # Jupyter notebook with full analysis
├── README.md # Project Documentation

## Steps and Instructions

Install VS Code using following instructions:
Download VS Code
Go to the official VS Code website and choose the appropriate version for your operating system.

Install VS Code
Run the .exe file,follow the setup instructions, and select necessary options like adding  VS code to path.

Launch VS Code
Open VS code and perform the task

Import required libraries
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt 
import seaborn as sns
from sklearn.preprocessing import LabelEncoder
from sklearn.preprocessing import MinMaxScaler
from sklearn.preprocessing import StandardScaler

# Load the Data
import pandas as pd
df = pd.read_csv('digital_marketing_campaign_dataset.csv')

# Data Cleaning
Handle missing values(drop or impute)
Detect and treat outliers(IQR method)
Encode categorical variables(label)
Normalize numeric features(standard scaler)

# Feature Engineering
Calculate CostperAcquisition, CTR and campaign duration

# Data Visualization
Conversion rate by channel
Feature correlation
Top and Underperforming Campaign
Relationship between AdSpend and ConverionRate
Customer segmentation
Timing Impact

# Next Steps
Build predictive models to forecast campaign success