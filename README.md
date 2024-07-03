<b>Dataset Overview:</b><br/>
This dataset comprises 303 entries and 14 attributes, including the 'Target' label. It includes both categorical and continuous variables.

<b>Data Cleaning:</b><br/>
Only one column has missing values, with just two entries missing, which can be easily handled by removing these rows using the dropna function.

<b>Data Visualization:</b><br/>
A detailed step-by-step analysis was performed, starting with a correlation matrix to identify the most significant variable related to the 'Target' label, which was found to be 'Age.' Additionally, graphs were plotted to illustrate the ratio of heart disease presence based on the 'Target' label.

<b>Methodology:</b><br/>
To address and resolve medical objectives, various data science techniques were applied to interpret the medical goals and diagnose heart disease. Several machine learning algorithms, including Random Forest, SVM (Support Vector Machine), Decision Tree, and Logistic Regression, were employed for training and implementation in Python to develop and enhance the predictive model. These algorithms aim to aid medical professionals in predicting and diagnosing heart attacks within the patient dataset. The primary goal was to determine which machine learning algorithm achieves the highest accuracy in predicting heart disease from the dataset.

<b>Results:</b><br/>
Cross-validation was conducted for all models, showing consistent results with slight variations in accuracy. The analysis concluded that Logistic Regression is the most suitable algorithm for this problem.

<b>Installation Guide:</b> <br/>
Install Anaconda Distribution.<br/>
Install Jupyter Notebook.<br/>
Launch Jupyter Notebook and open the file from its home page.