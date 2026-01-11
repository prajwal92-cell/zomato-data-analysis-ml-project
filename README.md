Problem Statement

In real-world data, restaurants differ in cost, cuisines, and other attributes. Identifying patterns and segments such as budget, mid-range, and premium restaurants can:
	•	Assist users in choosing restaurants based on their budget
	•	Help businesses understand competitive restaurant segments
	•	Provide insights into cost-related behaviors in the restaurant industry

This project uses unsupervised learning techniques to perform this segmentation without the need for consumer-labeled categories.

⸻

 Dataset

The dataset contains restaurant information collected from Zomato, including:
	•	Cost estimates per person
	•	Restaurant names
	•	Restaurant category/cuisines
	•	Other valuable metadata

(Include dataset source link or file name here if available)

⸻

 Methodology

 Data Cleaning & Preparation
	•	Handled missing values
	•	Cleaned cost column
	•	Converted textual categories into numeric encodings
	•	Scaled features for machine learning readiness

These steps help ensure the model works with quality data and improves clustering accuracy.

⸻

  Exploratory Data Analysis

Performed EDA to:
	•	Understand cost distribution
	•	Visualize relationships between key variables
	•	Identify trends and patterns before clustering

⸻

   Unsupervised Machine Learning: K-Means Clustering
	•	Used K-Means Clustering to segment restaurants based on cost and related features.
	•	The number of clusters was chosen using methods like the Elbow Method and Silhouette scores (if implemented in notebook).

  K-Means groups similar restaurants together based on feature similarity without using labeled targets. 
