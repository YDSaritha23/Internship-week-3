# Internship-week-3
The primary goal of this project is to preprocess a dataset for phishing detection by ensuring its readiness for machine learning model development
Objective
The primary goal of this project is to preprocess a dataset for phishing detection by ensuring its readiness for machine learning model development. The preprocessing includes data cleaning, feature encoding, normalization, and splitting into training and testing sets. This step-by-step process aims to create a clean, balanced, and well-structured dataset that will maximize model performance and reliability.

Key Tasks and Deliverables
1.	Data Cleaning Report:
o	Missing Values:
	The dataset was thoroughly checked for missing values, and none were identified. Therefore, no imputation techniques (e.g., mean, median, or mode) were required.
o	Duplicate Entries:
	Duplicate rows were analyzed, and none were found in the dataset. Thus, no duplicates were removed, ensuring all records in the dataset are unique.
2.	Feature Encoding Summary:
o	Encoding Techniques:
	Categorical features, such as forurl and status, were transformed using Label Encoding. Each unique category was assigned a unique numerical value.
	Example:
	status: legitimate → 0, phishing → 1.
o	Encoded Features:
	forurl: Each URL was encoded into integers for use in machine learning models.
	status: Encoded to serve as the target variable.
3.	Normalization/Scaling Report:
o	Technique Used:
	Min-Max Scaling was applied to all numerical features to scale them within the range [0, 1]. This ensures features are on a comparable scale, improving model training efficiency.
o	Impact of Scaling:
	Pre-normalization: Numerical features exhibited wide-ranging distributions.
	Post-normalization: All features were scaled uniformly, as confirmed by distribution summaries.
4.	Data Splitting Report:
o	Split Details:
	The dataset was divided into a training set (70%) and a testing set (30%) with stratification to maintain the balance of the target variable.
	Training Set: 8,001 records (50% class distribution).
	Testing Set: 3,429 records (50% class distribution).
o	Stratified Split:
	Ensured the status target variable maintained its proportional distribution across both sets.

Significance of the Project
Effective preprocessing is the foundation of robust machine learning. By eliminating noise, ensuring balanced target distributions, and scaling numerical features, this project sets the stage for building an accurate phishing detection model. The systematic approach taken ensures transparency, reproducibility, and high-quality data for downstream tasks.
________________________________________
