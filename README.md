# Sparkify_Capstone

![image](https://github.com/ishankcode/Sparkify_Capstone/assets/66678343/fb12b698-6008-42dc-8514-7cf633626be8)


# Project Objective
Sparkify is a music service platform like Spotify (Not real) and has a subscription-based model. Where the users have the option to either use it as paid (nominal fees) or free subscription (limited features). Users have the option to upgrade/downgrade or even cancel their plan altogether (left the app). Besides users have various features like adding songs to their playlists, researching songs from their favorite artists, sharing songs with friends, upvoting/downvoting songs based on their preferences, and much more.

The project's objective is to analyze customer churn and build a model for Sparkify to identify which customers will potentially churn. Using this analysis Sparkify can take proactive action and they can send various incentives to the customers to try to retain them as their customers. Some examples of incentives are:
1.	75% off for the next 3 months
2.	Enroll in the family plan and pay for 2 get 2 subscriptions for free.

# Steps
1.	Data cleaning – Dropping nulls, duplicates transforming data to correct format etc.
2.	Data exploration – Exploring data to understand each feature and extract crucial information regarding customer behavior.
3.	Feature Engineering – Toughest step of the project as identifying key features which are relevant to the model was crucial. There is a lot of scope for improvement in this step which will lead to the development of a better model.
4.	Defining Key Metrics- Identifying the presence of an imbalance in data, choosing correct metrics like F-1 Score, and justifying the selection of boosting and tree-based methods.
5.	Hypertuning the model and finding the best model using the cross-validation method.

# Result
On 12 gb (Dull dataset)

|Classification Methods|	Accuracy	|Precision	|Recall	|F-1 Score|
| :---:                | :---:      |:---:      | :---: | :---:   |
|Random Forest         |	0.78808	  |0.6703	    |0.7886	|0.72338  |
|Logistic Regression	 |0.8185	    |0.75264	  |0.8185	|0.7407   |
|GBT	                 |0.8134	    |0.7267	    |0.8127	|0.7416   |

Hypertuning parameters using cross-validation - 3 folds
|Classification Method	| Accuracy | Precision | Recall |	F-1 Score |
| :---:                 | :---:    | :---:     | :---:  | :---:     |
|Random Forest          |	0.81851	 | 0.6702	   | 0.8185 |	0.73707   |
|Logistics Regression	  |0.81706	 | 0.7555    | 0.81742|	0.74804   |




# Tools - Used
Python -  (Numpy, Pandas, Matplotlib, Scikit-Learn, stats, Pyspark)

AWS - (EMR Clusters - Jupyter Notebook, IAM, S3)

# AWS - configurations
![image](https://github.com/ishankcode/Sparkify_Capstone/assets/66678343/22f0106d-d5dd-4393-b1e3-79e89df10aad)
