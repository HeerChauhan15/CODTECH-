**Name**: Heer Chauhan <br>
**Company**: CODTECH IT SOLULTIONS <br>
**ID**: CS24NY354846 <br>
**DOMAIN**: DATA SCIENCE <br>
**DURATION**: DECEMBER TO JANUARY 2025 <br>

**OBJECTIVE** <br>

The objective of your Data Pipeline development project is to automate the ETL (Extract, Transform, Load) process. Specifically, you're focusing on data preprocessing and transformation to clean the dataset and prepare it for further analysis or modeling. The script you provided uses Pandas to:
<br>
1. **Extract** data from a CSV file.
2. **Transform** the data by handling missing values: filling missing values in the 'Age' column with the median, filling 'Cabin' with 'Unknown', and replacing missing 'Embarked' values with the most common value ('S').
3. **Load** the processed data by saving it to a new CSV file ('processed_titanic_data.csv').
This process helps to ensure the data is clean and ready for further steps like analysis or machine learning model development.
<br>

**Overview of the data** <br>

The Titanic dataset generally contains information about passengers on the RMS Titanic, which sank in 1912. The dataset typically includes the following columns: <br>
**PassengerId**: A unique identifier for each passenger.<br>
**Pclass**: The class of the ticket the passenger purchased (1st, 2nd, or 3rd class).<br>
**Name**: The name of the passenger.<br>
**Sex**: The gender of the passenger.<br>
**Age**: The age of the passenger, where missing values may need to be handled (filled with the median, as done in your task).<br>
**SibSp**: The number of siblings or spouses aboard the Titanic.<br>
**Parch**: The number of parents or children aboard the Titanic.<br>
**Ticket**: The ticket number.<br>
**Fare**: The fare the passenger paid for the ticket.<br>
**Cabin**: The cabin the passenger stayed in, which may contain missing or unknown values.<br>
**Embarked**: The port at which the passenger boarded the Titanic (C = Cherbourg; Q = Queenstown; S = Southampton). Missing values might need to be filled with the most common value. <br>
<br>
**Dataset Relevance to the Task:** <br>
**Preprocessing**: The task includes handling missing values in specific columns (e.g., 'Age', 'Cabin', and 'Embarked'). These are common preprocessing steps when dealing with real-world datasets.<br>
**Transformation**: The dataset may require transformation, such as encoding categorical variables (e.g., 'Embarked') for further analysis or modeling. In this case, 'Embarked' is transformed by filling missing values with the most common value ('S').<br>
**Loading**: The cleaned data is saved into a new file (processed_titanic_data.csv), which can later be used for further analysis, machine learning, or reporting.<br>
The goal of the data pipeline is to clean and transform this dataset, making it ready for analysis or model building, which aligns with your task objective.<br>

**Technologies Used** <br>
The technologies used in your Data Pipeline development task are:<br>

1. **Pandas**: For data manipulation, preprocessing, and handling missing values.
2. **Scikit-learn**: For potential feature transformation and machine learning model development.
3. **Python**: The primary programming language for automating the ETL process.
4. **Jupyter Notebook/Google Colab**: For interactive development, testing, and documentation.
5. **CSV Files**: For loading and saving the dataset.
6. **Git/GitHub**: For version control and collaboration.<br>

**Result** <br>
The result of the project is:<br>
1. **Cleaned Dataset**: Missing values in the 'Age', 'Cabin', and 'Embarked' columns are handled.
   - 'Age' is filled with the median value.
   - 'Cabin' is filled with 'Unknown'.
   - 'Embarked' is filled with 'S'
2. **Saved Processed File**: The cleaned data is saved as `processed_titanic_data.csv`.

3. **Automated ETL Script**: A Python script that automates the process of extracting, transforming, and loading the data.

4. **Completion Certificate**: Issued upon completion of the internship. <br>
![image](https://github.com/user-attachments/assets/746a2922-413a-4fc8-b161-b4fae0943a66)
