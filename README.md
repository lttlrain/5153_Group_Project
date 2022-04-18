# 5153_Group_Project

**Beware of Job Scams! Fake Job Prediction
Project: Detect fake job posts**

**Install**

This project requires Python 3.x and the following Python libraries installed:

•	NumPy

•	Pandas

•	matplotlib

•	seaborn

•	scikit-learn

•	Tensorflow Keras

•	Natural Language Toolkit

•	RegEx

•	Texthero

You will also need to have software installed to run and execute an iPython Notebook.

**Code**

Different machine learning models were explored and trained on the data. Each notebook file contains code for a specific machine learning model, 5153_GP_Model_XXX.ipynb. 

**Data**

The “final_dataset_for_modelling.csv” consists of approximately 17879 data points, with each datapoint having 40 features: 17 features were engineered from topic modelling, 17 features were missingness features engineered due to samples with missing features, 6 features were from the original dataset, with hot encoding applied on categorical features. This dataset is a modified version of the Employment  Scam Aegean Dataset (EMSCAD) downloaded from the Laboratory of Information   and Communication Systems Security, Department of Information and Communication Systems Engineering, at the University of Aegean. The EMSCAD   contains 17,880 job advertisements published on a recruitment software between 2012 and 2014; each job advertisement was classified as either fraudulent or not fraudulent by specialized employees of the recruitment software. 

**Original Data Features**

•	Job ID: Serial number (e.g., 1)

•	Title: Title (e.g., Infrastructure Engineer)

•	Job Location: Geographical location(e.g., US, CA, California)

•	Job Department: Corporate department(e.g., Accounting)

•	Job Salary: Indicative salary range(e.g., $7000-$9000)

•	Company Profile: Company description(e.g., “Our mission to clients is ...”)

•	Job Descriptions: Job description(e.g., “Drive the sales effort ...”)

•	Job Requirements: Job requirements(e.g., “Proven leadership experience ...”)

•	Job Benefits: Job benefits(e.g., “Fun, supportive team ...”)

•	Telecommuting: Telecommuting position(1 = Yes; 0 = No)

•	Company Logo: Presence of company logo(1 = Yes; 0 = No)

•	Questions: Presence of screening questions(1 = Yes; 0 = No)

•	Employment Type: Employment type (e.g., Full-Time, Part-Time)

•	Required Experience: Required experience (e.g., Entry-Level, Mid-Senior Level)

•	Required Education: Required education (e.g., Bachelor’s Degree, Master’s Degree)

•	Job Industry: Industry (e.g., Banking, Design)

•	Job Function: Function (e.g.,Administrative, Advertising)

**Target Variable**

•	fraudulent: Fraudulence (1 = Fraudulent; 0 = Not Fraudulent)
