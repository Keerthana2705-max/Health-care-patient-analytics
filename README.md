<h1>Healthcare Analytics System (Synthetic Data)</h1>
<p>Exploratory Data Analysis (EDA) Project</p>
<p>Overview</p>
<p>This project focuses on analyzing patient health data using a synthetically generated dataset. Healthcare institutions generate vast amounts of patient information, but manual analysis is inefficient, time-consuming, and prone to errors.
Due to privacy concerns, real-world patient datasets are often unavailable for academic use. Therefore, this project simulates realistic healthcare data and applies data analysis techniques to extract meaningful insights.</p>
<p>The workflow includes:</p>
Synthetic data generation using Python <br>
Data preprocessing and cleaning <br>
Exploratory Data Analysis (EDA) <br>
Risk classification of patients <br>
Data visualization <br>
Insight generation <br>
<p>The objective is to build a structured and scalable analytics system that can help in identifying high-risk patients and supporting healthcare decision-making.</p>
<p>Dataset</p>
<p>Source: Synthetic (Randomly Generated Dataset using Python & Faker)</p>
<p>Description:</p>
<p>The dataset contains 10,000 patient records with the following attributes:</p>
<p>Column Name:	Description<br>
Patient_ID:	Unique identifier<br>
Age:	20–80<br>
Gender:	Male / Female<br>
Blood_Pressure:	80–180<br>
Sugar_Level:	70–200<br>
Cholesterol:	150–300<br>
Heart_Rate:	60–120<br></p>

<p>Objectives</p>

<p>Generate a realistic synthetic healthcare dataset<br> 
Perform data cleaning and preprocessing <br>
Compute statistical measures (mean, median, standard deviation)<br> 
Analyze key health parameters: <br>
oBlood pressure<br> 
oSugar levels <br>
oCholesterol <br>
oHeart rate <br>
Classify patients into risk levels (Low, Medium, High)<br> 
Identify high-risk patients for early intervention <br>
Perform group-based analysis: <br>
oAge group vs health condition <br>
oGender-wise comparison <br>
oRisk distribution <br>
Study relationships between variables:<br> 
oBlood pressure vs age <br>
oCholesterol vs heart rate <br>
oSugar level vs risk <br>
Visualize data using multiple charts<br> 
Derive actionable healthcare insights <br></p>

<p>Project Highlights</p>

<p>1. Data Preprocessing</p>
<p>Checked for missing values and ensured data consistency <br>
Generated clean and structured dataset <br>
Created additional features: <br>
oRisk Level (Low / Medium / High) <br>
oAge Groups (Young, Adult, Mid-Age, Senior)<br> 
</p>
<p>2. Exploratory Data Analysis (EDA)</p>
<p>
Analyzed distributions using histograms<br> 
Studied relationships using scatter plots <br>
Used box plots to detect outliers <br>
Evaluated correlations using heatmaps <br></p>

<p>3. Risk Classification</p>
<p>Patients were classified based on medical thresholds:</p>
<p>Low Risk: Normal health parameters <br>
Medium Risk: Moderate abnormalities <br>
High Risk: Multiple abnormal conditions <br>
Criteria included:<br>
High blood pressure <br>
High sugar levels <br>
High cholesterol <br>
Elevated heart rate <br></p>

<p>4. Group-Based Analysis</p>
<p>
Age Group Analysis: Older patients tend to show higher risk <br>
Gender Analysis: Compared average health metrics across genders <br>
Risk Distribution: Identified proportion of patients in each risk category<br> 
</p>

<p>5. Visualization</p>
<p>The project includes the following visualizations:</p>
<p>Bar charts (Age group vs Risk level) <br>
Pie charts (Risk distribution) <br>
Histograms (Health parameter distributions)<br> 
Scatter plots (Age vs Blood Pressure) <br>
Box plots (Outlier detection) <br>
Heatmaps (Correlation analysis) <br></p>

<p>Tools and Technologies</p>
<p>
Python <br>
pandas <br>
numpy <br>
matplotlib<br> 
seaborn <br>
Faker (for synthetic data generation) <br>
Jupyter Notebook <br></p>

<p>Results</p>
<p>Key Findings</p>
<p>Blood pressure tends to increase with age<br> 
High sugar and cholesterol significantly contribute to higher risk levels<br> 
A portion of patients fall into the high-risk category requiring attention <br>
Strong relationships exist between multiple health parameters <br>
Outliers were identified in several health metrics <br></p>

<p>Interpretation</p>
<p>Risk Identification: The system effectively identifies high-risk patients<br> 
Preventive Insight: Early detection helps reduce serious health complications<br> 
Correlation Strength: Health parameters are interrelated <br>
Data Simulation Value: Synthetic data is useful for academic and research purposes<br> </p>
<p>Conclusion</p>
<p>This project demonstrates how synthetic healthcare data combined with EDA techniques can be used to analyze patient health effectively.</p>
<p>The structured workflow improves:</p>
Data understanding <br>
Risk detection <br>
Healthcare decision-making<br> 
<p>This system can be extended to real-world datasets for better patient monitoring and predictive analytics.</p>
