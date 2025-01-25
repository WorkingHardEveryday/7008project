# Customer Experience Analysis in E-commerce

### Project Description
Clickstream analysis in online retails or physical store is one of the hot topics.  This project aims to perform a customer behavior analysis from online store visit clickstream.  

### Project Objectives 
#### 1.Behavioral Analysis:

Apply EDA and identify patterns in customer behavior such as browsing habits, time spent on pages, and frequently visited sections.

#### 2.Customer Segmentation:

Segment customers based on their behavior, purchase history, and demographics to tailor marketingstrategies. 

#### 3.Conversion Rate Optimization:
Analyze the customer journey to predict and optimize the purchase rate. I apply a Random Forest model to identify the features that have the most significant impact on user conversion rates based on the dataset. I further investigate how changes in various features influence conversion rates by integrating an A/B testing approach. Then, I use Random Forest Regressor to calculate the percentage improvement in the purchase rate when we increase the value of certain attributes by a specific percentage. 

#### 4. Interactive Interface:
Create a GUI interactive interface that enables users to view the importance of different customer purchasing features.

### Data Sources:
The data set and description are introduced in the link: https://www.kaggle.com/datasets/henrysue/online-shoppers-intention. The dataset I use is The Intentions of Online Shoppers and it consists of feature vectors belonging to 12,330 sessions. The dataset is formed in a way that each session belongs to a different user within one year to avoid any tendency towards a particular campaign, special day, user profile or period.

The structure of the attributes is changed on both categorical and numerical basis. For modeling, the categorical attributes are converted into ordinal factor variables and numerically coded. The numerical variables of the dataset are normalized for clustering methods and scaled for categorical methods.
































