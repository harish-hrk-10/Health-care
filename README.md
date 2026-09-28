# 🏥 Healthcare Data Analysis and Visualization

## 📌 Project Overview

This project performs **exploratory data analysis (EDA)** on a healthcare dataset containing patient information, medical conditions, admission types, and other hospital-related details.

The analysis uses **Python, Pandas, Matplotlib, and Seaborn** to understand patient demographics and healthcare admission patterns through different visualizations.

## 📊 Dataset

The dataset contains:

* **54,966 patient records**
* **18 columns**

### Dataset Features

| Column             | Description                 |
| ------------------ | --------------------------- |
| Name               | Patient name                |
| Age                | Patient age                 |
| Gender             | Patient gender              |
| Blood_Type         | Patient blood type          |
| Medical_Condition  | Patient's medical condition |
| Admission_Date     | Date of admission           |
| Doctor             | Assigned doctor             |
| Hospital           | Hospital name               |
| Insurance_Provider | Insurance provider          |
| Billing_Amount     | Hospital billing amount     |
| Room Number        | Patient room number         |
| Admission_Type     | Type of admission           |
| Discharge_Date     | Date of discharge           |
| Medication         | Medication information      |
| Test_Results       | Medical test results        |
| Length_of_Stay     | Duration of hospital stay   |
| Age_Group          | Patient age group           |
| Admission_Urgency  | Admission urgency           |

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

## 🔍 Analysis Performed

### 1. Patient Age Distribution

A histogram with KDE is used to visualize the distribution of patient ages.

### 2. Age Distribution by Gender

The project compares patient age distributions across different genders.

### 3. Patient Distribution by Gender

A bar chart shows the number of patients belonging to each gender category.

### 4. Patients by Medical Condition

The project analyzes the number of patients associated with different medical conditions.

The conditions included in the dataset are:

* Arthritis
* Asthma
* Cancer
* Diabetes
* Hypertension
* Obesity

### 5. Gender Distribution Across Medical Conditions

A count plot is used to examine gender distribution for each medical condition.

### 6. Admission Type Analysis

The project analyzes the distribution of:

* Elective
* Emergency
* Urgent

admission types.

### 7. Medical Condition vs Admission Type

A cross-tabulation is created to compare medical conditions with admission types.

The resulting counts are:

| Medical Condition | Elective | Emergency | Urgent |
| ----------------- | -------: | --------: | -----: |
| Arthritis         |     3062 |      3073 |   3083 |
| Asthma            |     3069 |      2978 |   3048 |
| Cancer            |     3114 |      2988 |   3038 |
| Diabetes          |     3031 |      2988 |   3197 |
| Hypertension      |     3182 |      2975 |   2994 |
| Obesity           |     3015 |      3100 |   3031 |

A stacked bar chart is also used to visualize these relationships.

## 📈 Visualizations

The notebook generates visualizations for:

* Patient age distribution
* Patient age distribution by gender
* Gender-wise patient count
* Medical condition distribution
* Gender distribution across medical conditions
* Admission type distribution
* Admission type across medical conditions

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone <your-repository-url>
```

### 2. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### 3. Open the notebook

Open:

```text
w6.ipynb
```

using **Jupyter Notebook**, **JupyterLab**, or **Google Colab**.

### 4. Provide the dataset

The notebook currently loads the dataset using:

```python
df = pd.read_csv("/content/healthcare_preprocessed")
```

Update the file path if your dataset is stored in a different location.

## 🎯 Project Objectives

* Understand the structure of healthcare data
* Explore patient demographics
* Analyze medical condition frequencies
* Study admission type patterns
* Compare medical conditions with admission types
* Create meaningful visualizations from healthcare data
* Practice exploratory data analysis using Python

## 📁 Project Structure

```text
Healthcare-Data-Analysis/
│
├── w6.ipynb
├── healthcare_preprocessed
└── README.md
```

## 👨‍💻 Author

**Harish M**

This project was developed as part of data analysis practice using Python.
