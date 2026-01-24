# 📊 Descriptive Statistics Case Study on Employee Dataset

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## � Table of Contents
- [Project Overview](#-project-overview)
- [Objectives](#-objectives)
- [Dataset Description](#-dataset-description)
- [Tech Stack & Libraries](#️-tech-stack--libraries)
- [Project Structure](#-project-structure)
- [Installation & Setup](#-installation--setup)
- [Analysis Workflow](#-analysis-workflow)
- [Key Findings](#-key-findings)
- [Visualizations](#-visualizations)
- [Conclusion](#-conclusion)
- [Author](#-author)

---

## 📝 Project Overview

This project is a comprehensive **Descriptive Statistics Case Study** that analyzes an **Employee Dataset** to uncover meaningful patterns, distributions, and insights about workforce characteristics. The analysis focuses on understanding employee demographics, health behaviors, and salary distributions using statistical measures and data visualization techniques.

Descriptive statistics is a fundamental branch of statistics that helps summarize and describe the main features of a dataset. This project demonstrates how to apply these concepts in a real-world scenario using Python and popular data science libraries.

---

## 🎯 Objectives

The primary objectives of this case study are:

### 1. Data Loading & Cleaning
- Import the employee dataset into a pandas DataFrame
- Check for missing values and handle data inconsistencies
- Rename columns for better clarity and understanding
- Verify data types and ensure numerical columns are correctly formatted

### 2. Exploratory Data Analysis (EDA)
- Understand the structure and shape of the dataset
- Identify unique categories (e.g., Blood Groups)
- Generate summary statistics for all numerical columns

### 3. Central Tendency Analysis
- **Mean**: Calculate the average value for each numerical variable
- **Median**: Find the middle value to understand central position
- **Mode**: Identify the most frequently occurring values

### 4. Dispersion Analysis
- **Minimum & Maximum**: Determine the range of values
- **Range**: Calculate the spread between min and max
- **Standard Deviation**: Measure the amount of variation in the data
- **Variance**: Understand how data points differ from the mean

### 5. Data Visualization
- Create histograms to visualize distributions
- Generate box plots to identify outliers
- Build correlation heatmaps to understand relationships
- Compare statistics across different groups (Blood Groups)

### 6. Insights & Conclusions
- Draw meaningful conclusions from the statistical analysis
- Identify patterns and trends in employee data
- Provide actionable insights based on the findings

---

## 📂 Dataset Description

The dataset contains **50 employee records** with **6 attributes**. Below is a detailed description of each column:

| Column Name | Data Type | Description |
|-------------|-----------|-------------|
| `Employee_ID` | Integer | Unique identifier for each employee (0-49) |
| `Blood_Group` | Categorical | Blood group of the employee (A, B, AB, O) |
| `Age` | Integer | Age of the employee in years (22-62) |
| `Healthy_Eating_Score` | Integer | Self-reported score for healthy eating habits (1-9) |
| `Active_Lifestyle_Score` | Integer | Self-reported score for physical activity level (1-10) |
| `Salary` | Integer | Annual salary of the employee in currency units (556-4969) |

### Blood Group Distribution
- **Group A**: 20 employees (40%)
- **Group O**: 18 employees (36%)
- **Group AB**: 6 employees (12%)
- **Group B**: 6 employees (12%)

---

## 🛠️ Tech Stack & Libraries

The analysis is performed using **Python 3.8+** and the following libraries:

| Library | Version | Purpose |
|---------|---------|---------|
| **Pandas** | 2.x | Data manipulation, loading CSV, DataFrame operations |
| **NumPy** | 1.x | Numerical computations, array operations |
| **Matplotlib** | 3.x | Creating static visualizations (histograms, bar charts) |
| **Seaborn** | 0.12+ | Statistical data visualization with aesthetic themes |
| **SciPy** | 1.x | Scientific computing and advanced statistical functions |

---

## 📁 Project Structure

```
Descriptive-Statistics-Case-Study-on-Employee-Dataset/
│
├── 📓 Descriptive_Statistics_Case_Study.ipynb   # Main Jupyter Notebook with analysis
├── 📊 Employee Dataset.csv                       # Raw dataset file
├── 📄 README.md                                  # Project documentation (this file)
└── 📜 LICENSE                                    # License file (if applicable)
```

---

## 🚀 Installation & Setup

Follow these steps to run the project on your local machine:

### Prerequisites
- Python 3.8 or higher installed
- Jupyter Notebook or JupyterLab (or VS Code with Jupyter extension)
- Git (for cloning the repository)

### Step 1: Clone the Repository
```bash
git clone https://github.com/Piyu242005/Descriptive-Statistics-Case-Study-on-Employee-Dataset.git
```

### Step 2: Navigate to the Project Directory
```bash
cd Descriptive-Statistics-Case-Study-on-Employee-Dataset
```

### Step 3: Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
```

### Step 4: Install Required Dependencies
```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

### Step 5: Launch Jupyter Notebook
```bash
jupyter notebook
```

### Step 6: Open the Analysis Notebook
Open `Descriptive_Statistics_Case_Study.ipynb` in the Jupyter interface to view and run the analysis.

---

## 📈 Analysis Workflow

The analysis follows a structured workflow as outlined below:

```
┌─────────────────────┐
│  1. Load Dataset    │
└─────────┬───────────┘
          ▼
┌─────────────────────┐
│  2. Data Cleaning   │
│  - Missing values   │
│  - Rename columns   │
└─────────┬───────────┘
          ▼
┌─────────────────────┐
│  3. Data Overview   │
│  - Shape & types    │
│  - Unique values    │
└─────────┬───────────┘
          ▼
┌─────────────────────┐
│  4. Descriptive     │
│     Statistics      │
│  - Central Tendency │
│  - Dispersion       │
└─────────┬───────────┘
          ▼
┌─────────────────────┐
│  5. Visualization   │
│  - Histograms       │
│  - Box plots        │
│  - Heatmaps         │
└─────────┬───────────┘
          ▼
┌─────────────────────┐
│  6. Conclusions     │
└─────────────────────┘
```

---

## 🔍 Key Findings

### Age Statistics
| Measure | Value |
|---------|-------|
| Mean | 31.88 years |
| Median | 30.00 years |
| Mode | 30.00 years |
| Min | 22 years |
| Max | 62 years |
| Std Dev | 8.39 years |

### Salary Statistics
| Measure | Value |
|---------|-------|
| Mean | ₹2,027.50 |
| Median | ₹1,950.00 |
| Mode | ₹1,134.00 |
| Min | ₹556 |
| Max | ₹4,969 |
| Std Dev | ₹1,076.86 |

### Health & Lifestyle Scores
- **Healthy Eating Score**: Average of 4.92 out of 10 (indicates room for improvement)
- **Active Lifestyle Score**: Average of 5.90 out of 10 (moderate activity levels)

---

## 📊 Visualizations

The notebook includes the following visualizations:

1. **Distribution Plots**: Histograms showing the distribution of Age, Salary, and Scores
2. **Box Plots**: Identifying outliers and understanding data spread
3. **Count Plots**: Visualizing employee distribution by Blood Group
4. **Correlation Heatmap**: Understanding relationships between numerical variables
5. **Group Comparisons**: Statistics compared across different Blood Groups

---

## 📌 Conclusion

This case study demonstrates the power of descriptive statistics in understanding workforce data. Key takeaways include:

1. **Age Distribution**: The workforce is relatively young with a mean age of ~32 years
2. **Salary Variation**: High variability in salaries (std dev of ~₹1,077) suggests diverse roles or experience levels
3. **Health Awareness**: Both healthy eating and active lifestyle scores hover around the midpoint, indicating potential for wellness programs
4. **Data Quality**: The dataset is clean with no missing values, making it ideal for statistical analysis

---

## 👨‍💻 Author

**Piyu**

- GitHub: [@Piyu242005](https://github.com/Piyu242005)
- Project: Descriptive Statistics Learning Project (Internship)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ **If you find this project helpful, please consider giving it a star!**
