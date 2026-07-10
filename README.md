Exploratory Data Analysis (EDA) on Retail Sales Data

📌 Overview

This project performs Exploratory Data Analysis (EDA) on a retail sales dataset using Python. The notebook loads transaction-level sales data and analyzes customer demographics, product category performance, and sales trends over time to surface actionable business insights.

🗂️ Dataset


File: retail_sales_dataset.csv
Loaded via: Google Colab file upload (google.colab.files.upload())
Key columns used in the analysis:

Date – transaction date (converted to datetime)
Customer ID – unique customer identifier
Gender – customer gender
Age – customer age
Product Category – category of the purchased product
Total Amount – transaction sales value





🛠️ Tools & Libraries


Language: Python (Jupyter / Google Colab)
Libraries:

pandas, numpy – data manipulation
matplotlib, seaborn – data visualization





📊 Analysis Workflow


Data Loading – Import the CSV dataset into a pandas DataFrame
Initial Inspection – Check shape, columns, and data types (df.info())
Data Quality Checks – Identify missing values (df.isnull().sum()) and duplicate rows (df.duplicated().sum())
Descriptive Statistics – Summary statistics with df.describe()
Data Type Conversion – Convert Date column to datetime format
Demographic Analysis

Gender distribution (count plot)
Age distribution (histogram)



Product Analysis

Product category distribution
Total sales by product category (bar chart)



Sales by Gender – Compare total sales contributed by each gender
Time Series Analysis – Monthly sales trend (line plot with markers)
Correlation Analysis – Heatmap of correlations between numeric variables
Customer Analysis – Top 10 customers ranked by total spending
Age Group Segmentation – Bucket customers into age groups (0–20, 21–30, 31–40, 41–50, 50+) and compare sales by group


🔍 Key Insights

(Fill in with your actual results once you review the plots — a few starter prompts based on the analysis above)


Which product category generates the most revenue?
Does one gender contribute significantly more to total sales?
Which months show peak sales — is there a seasonal trend?
Who are the top 10 highest-spending customers?
Which age group drives the most revenue?
Are there strong correlations between numeric features (e.g., Age, Quantity, Total Amount)?


📁 Repository Structure

├── retail_eda.ipynb          # Main EDA notebook
├── retail_sales_dataset.csv  # Dataset (if included in repo)
└── README.md                 # Project documentation

🚀 How to Run


Clone the repository


bash   git clone https://github.com/prince7046/Exploratory-Data-Analysis-EDA-on-Retail-Sales-Data.git
   cd Exploratory-Data-Analysis-EDA-on-Retail-Sales-Data


Install dependencies


bash   pip install pandas numpy matplotlib seaborn


Open the notebook in Jupyter or Google Colab


bash   jupyter notebook retail_eda.ipynb


If running in Colab, upload retail_sales_dataset.csv when prompted by the file upload cell.


✅ Conclusion

This EDA provides a clear view of retail sales performance across customer demographics (age, gender), product categories, and time. The insights can help guide marketing focus, inventory planning, and customer targeting strategies.

👤 Author

Prince
🔗 [GitHub Profile](https://github.com/prince7046)

📄 License

This project is licensed under the MIT License.
