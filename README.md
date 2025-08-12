
### Setup Instructions
1. Create a virtual environment (recommended):
	```powershell
	python -m venv venv
	.\venv\Scripts\activate
	```
2. Install dependencies:
	```powershell
	pip install -r requirements.txt
	```

### Usage
	- Perform Exploratory Data Analysis (EDA) on customer data, including statistics, visualizations, and insights.
	- Apply feature engineering techniques such as normalization, one-hot encoding, binning, and creation of new features.

#### EDA Steps Covered in the Notebook
- Data cleaning (removing duplicates, extracting features, formatting columns)
- Statistical analysis (mean, median, mode, variance, standard deviation)
- Data visualization (histograms, bar charts)
- Grouped analysis (mean spending score by city)

#### Feature Engineering Steps Covered in the Notebook
- Creation of new features (average spend per transaction, transactions per month)
- One-hot encoding of categorical variables (city)
- Binning and categorization (age group, income group, recency category)
- Standardization of numerical features
- Identification of high spenders
