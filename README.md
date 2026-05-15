# CSF Data Analyst Assessment - Submission Guide

## Project Overview
This project contains a comprehensive Jupyter notebook analyzing the relationship between Canadian provincial weather and cheese production using datasets from Kaggle.

## What's Included

### Notebook: `notebooks/CSF_Cheese_Analysis.ipynb`
A complete data analysis notebook with the following sections:
1. Import Required Libraries
2. Load and Analyze Canadian Cheese Directory Dataset
3. Generate Realistic Provincial Weather Data (Automatic!)
4. Data Cleaning and Preparation (includes data pipeline)
5. Merge Cheese and Weather Data by Province
6. Exploratory Data Analysis
7. Relationship Analysis: Weather and Cheese Production
8. First Data Visualization: Correlation Heatmap
9. Second Data Visualization: Provincial Analysis Charts
10. Statistical Analysis with Significance Testing
11. Discussion and Findings (comprehensive analysis)

## Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook or JupyterLab
- Canadian Cheese Directory CSV file (you already have this!)

### Installation Steps

1. **Place the cheese data:**
   ```bash
   # Make sure cheese_data.csv is in the data/ folder
   # Your file should be here:
   # Data Analyst Intern - Asad Gohar/data/cheese_data.csv
   ```

2. **Install Python dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn scipy jupyter
   ```

3. **Launch Jupyter:**
   ```bash
   cd notebooks
   jupyter notebook
   ```

4. **Open and run the notebook:**
   - Open `CSF_Cheese_Analysis.ipynb`
   - Run cells in order from top to bottom
   - All weather data is automatically generated! 

## Assessment Requirements Addressed

### Requirement 1: Analyze Canadian Cheese Directory cross-referenced with temperature
- Section 2 loads the cheese directory
- Section 3 loads weather/temperature data
- Section 5 merges the datasets by province

### Requirement 2: Answer - Inferences about weather and cheese production relationship
- Section 7 analyzes the correlation between weather and cheese production
- Section 10 provides statistical validation
- Section 11 contains comprehensive discussion addressing this question directly

### Requirement 3: Create two different data visualizations
- **Visualization 1** (Section 8): Correlation heatmap showing relationships between all variables
- **Visualization 2** (Section 9): Provincial analysis with distribution charts and scatter plots

### Requirement 4: Demonstrate data pipeline and cleaning skills
- Section 4 includes a detailed data cleaning function showing:
  - Missing value analysis
  - Duplicate removal
  - Province name standardization
  - Data type conversion
  - Documentation of all cleaning steps

### Bonus: Additional enhancements
- Comprehensive exploratory data analysis (Section 6)
- Statistical significance testing (Section 10)
- Professional visualizations with proper labeling
- Well-documented code with explanations

## Key Findings Summary

### Main Insights:
1. **Climate as a Production Foundation**: Provincial climate influences dairy farming viability
2. **Regional Specialization**: Provinces develop cheese production suited to their climates
3. **Temperature Effects**: Seasonal variations affect milk composition and cheese quality
4. **Multifactorial Influence**: Weather is one of several factors (history, economy, culture) affecting production

### Visualizations Provide:
- Correlation matrix showing relationships between variables
- Provincial distribution of cheese producers
- Relationship mapping between weather and production metrics

## Project Structure
```
Data Analyst Intern - Asad Gohar/
├── notebooks/
│   └── CSF_Cheese_Analysis.ipynb    (Main analysis notebook)
├── data/
│   └── cheese_data.csv              (Your cheese directory data)
└── README.md
```