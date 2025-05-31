# DATA-PIPELINE-DEVELOPMENT

*COMPANY*: CODTECH IT SOLUTIONS PVT LTD

*NAME*: Pooja Charpe

*INTERN ID*: CT12WU77

*DOMAIN*:  Data Science

*DURATION*: 12 Weeks

*MENTOR*: Neela Santosh

**The internship task focused on building an **ETL (Extract, Transform, Load) pipeline** using Python to clean and prepare raw data for analysis. This process was automated through a Python script written in Jupyter Notebook, a popular interactive editor platform used widely in data science for combining code, outputs, and explanations in one place.

The task began by **extracting** raw data from a .csv file using the pandas library, which allowed efficient loading into a structured DataFrame. Once loaded, the **transform** phase tackled the common issues seen in raw datasets. Numeric columns often had missing values; these were imputed using the mean to avoid introducing bias or gaps. Categorical columns were filled with a placeholder like 'missing' to keep category mappings intact.

To ensure the numeric data was suitable for machine learning algorithms, the script applied **StandardScaler** from scikit-learn, which standardized each numeric feature by removing the mean and scaling to unit variance. This is especially important for models that are sensitive to scale, such as logistic regression or SVMs. Categorical variables, on the other hand, were encoded using OneHotEncoder, which converts categories into binary columns, making them machine-readable.

Finally, the cleaned, transformed dataset was loaded back to disk as a new .csv file, ready for further analysis or modeling.


**Tools Used**

Python: Main programming language for the task.

pandas: For data loading, manipulation, and saving.

scikit-learn: For preprocessing tasks like scaling and encoding.

Jupyter Notebook: The editor platform, allowing interactive development and clear step-by-step execution.


**Where It’s Applicable**

This kind of pipeline is highly applicable in real-world settings. For example:

In **business analytics**, it prepares sales or customer data for dashboards and KPI tracking.

In **finance**, it ensures credit or risk data is cleaned before feeding into scoring models.

In **healthcare**, it handles messy patient records for clinical prediction tools.

In **e-commerce**, it transforms customer behavior data for recommendation systems.


*OUTPUT*: 

![Image](https://github.com/user-attachments/assets/a34f990c-947d-456d-b6b6-fa1557941d8f)

**
