# Employee Data Processing & Dataset Automation using Python

## 📌 Project Overview

This project demonstrates practical Python-based data processing and dataset automation using **Pandas, NumPy and Python**.

The project is based on a scenario where an organisation has hired 1,000 new employees and needs to transform a raw text file containing employee names into a structured employee dataset.

The workflow includes generating employee IDs, email IDs and passwords, creating and manipulating a Pandas DataFrame, validating the dataset, identifying duplicate email addresses, filtering employee records, removing specific records and exporting the processed data to Excel.

## 🎯 Project Objectives

The main objectives of this project were to:

* Load employee names from a text file
* Generate unique employee IDs starting from `2020001`
* Generate employee email IDs using the required format
* Generate passwords containing uppercase letters, lowercase letters, numbers and special characters
* Create a structured Pandas DataFrame
* Inspect and validate the dataset
* Retrieve employee records using Pandas
* Check for duplicate email addresses
* Resolve duplicate email IDs
* Create a filtered batch of employees whose names start with "A"
* Remove employees who are no longer joining
* Create a password-free DataFrame for data sharing
* Export processed data to Excel
* Read the Excel dataset back into Pandas

## 🛠️ Technologies & Libraries

* **Python**
* **Pandas**
* **NumPy**
* **Random**
* **Jupyter Notebook**
* **Microsoft Excel**
* **openpyxl**

## 🔄 Project Workflow

### 1. Data Loading

The employee names were loaded from an external text file, with each employee name stored on a separate line.

### 2. Employee ID Generation

Employee IDs were automatically generated starting from:

```text
2020001
2020002
2020003
...
```

### 3. Email ID Generation

Email addresses were generated using the required structure:

```text
first_name.last_name@edureka.co
```

### 4. Password Generation

A Python-based password generation process was implemented using:

* Uppercase letters
* Lowercase letters
* Numbers
* Special characters

### 5. DataFrame Creation

The generated employee information was organised into a Pandas DataFrame containing:

| Column      | Description                |
| ----------- | -------------------------- |
| Names       | Employee names             |
| Employee ID | Unique employee identifier |
| Email ID    | Generated employee email   |
| Password    | Generated password         |

### 6. Data Validation & Inspection

The dataset was inspected using Pandas operations to examine:

* First and last records
* DataFrame shape
* Data types
* Dataset size
* Individual employee records
* Email values
* Duplicate email addresses

### 7. Duplicate Email Handling

The project checks for duplicate email addresses and modifies duplicated email IDs by adding a number to maintain uniqueness.

### 8. Data Filtering

A separate employee batch was created containing employees whose names start with the letter **"A"**, along with the total number of matching employees.

### 9. Record Removal

Three employee records were removed based on the specified indexes because those employees were no longer joining the organisation.

### 10. Data Sharing

A separate DataFrame was created without the password column before exporting the employee information to Excel.

This demonstrates the importance of removing sensitive information before sharing datasets with other departments.

### 11. Excel Export & Retrieval

The processed dataset was exported to an Excel file and subsequently accessed using Pandas.

Employee information can then be retrieved using name-based filtering.

## 📊 Key Skills Demonstrated

* Python Programming
* Pandas
* NumPy
* Data Manipulation
* Data Cleaning
* Data Preprocessing
* Data Validation
* Data Filtering
* DataFrame Indexing
* Duplicate Detection
* Dataset Transformation
* File Handling
* Excel Data Processing
* Jupyter Notebook

## 📁 Project Structure

```text
employee-data-processing-python/
│
├── main(1).ipynb
├── names.txt
├── data_without_pass.xlsx
└── README.md
```

> **Security Note:** Password-containing datasets should not be uploaded to a public repository. The password-free dataset is intended for safe sharing and demonstration purposes.

## 💡 Key Learning Outcomes

Through this project, I developed practical experience in transforming raw data into structured datasets and performing common data-processing operations using Python and Pandas.

The project also provided hands-on experience with data validation, duplicate handling, filtering, DataFrame manipulation and Excel integration.

## 🚀 Future Improvements

Potential future enhancements include:

* Adding more robust data validation
* Automating duplicate email handling for larger datasets
* Improving password-generation security
* Adding data visualisations
* Building an interactive dashboard
* Connecting the workflow to a database
* Developing a reusable data-processing pipeline

## 👨‍💻 Author

**Mohd Ravish**

Aspiring Data Analyst | Python | Pandas | Data Analytics | Finance
