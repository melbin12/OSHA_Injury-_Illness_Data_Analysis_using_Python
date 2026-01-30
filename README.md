# 📊 OSHA Injury & Illness Data Analysis using Python

## 🔍 Overview
This project conducts an in-depth **Exploratory Data Analysis (EDA)** and **Data Preprocessing** pipeline on the **OSHA Injury & Illness Summary Dataset** (Form 55). The analysis transforms raw operational safety data into actionable business intelligence through comprehensive data cleaning, statistical analysis, and interactive visual storytelling.

## 📁 Dataset Information
- **Source:** U.S. Department of Labor - Occupational Safety and Health Administration
- **Dataset:** Injury & Illness Summary — Operational Source Data (Form 55)
- **Records:** 390,555 entries across 28 columns
- **Time Span:** Multiple years of railroad industry safety data
- **Key Metrics:** Injury reports, train miles, employee hours, passenger volumes

## 🎯 Project Objectives
1. **Data Preparation & Cleaning**
   - Handle missing values and outliers systematically
   - Standardize data formats and types
   - Ensure data quality for reliable analysis

2. **Exploratory Data Analysis (EDA)**
   - Identify patterns, trends, and anomalies
   - Conduct statistical analysis of safety metrics
   - Document findings with clear, reproducible steps

3. **Advanced Visualization**
   - Create 4 static visualizations for quick insights
   - Develop 8 interactive Plotly charts for deeper exploration
   - Design dashboards suitable for stakeholder presentations

4. **Business Intelligence**
   - Extract actionable safety insights
   - Provide data-driven recommendations
   - Support decision-making for operational improvements

## 🛠️ Technical Implementation

### **Tools & Technologies**
- **Python Ecosystem:** pandas, NumPy, SciPy
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Environment:** Jupyter Notebook, Google Colab
- **Analysis:** Statistical methods, data transformation

### **Methodology**
1. **Data Loading & Initial Assessment**
   - Import and inspect dataset structure
   - Analyze data types and completeness
   - Establish baseline understanding

2. **Data Cleaning Pipeline**
   - Type conversion for numeric fields
   - Strategic missing value imputation
   - Outlier detection and removal using Z-score method

3. **Analytical Approach**
   - Comparative analysis across railroads and regions
   - Temporal trend identification
   - Correlation studies between operational metrics and incidents

4. **Visual Storytelling**
   - Combination of static and interactive charts
   - Geographic mapping of safety incidents
   - Time-series analysis of reporting patterns

## 📊 Key Analytical Components

### **Data Quality Assessment**
- Initial dataset shape: 390,555 × 28
- Missing value analysis for each column
- Data type standardization across numeric and categorical fields

### **Visualization Portfolio**
#### **Static Visualizations (4)**
1. Top Reporting Railroads - Bar Chart
2. Total Miles Distribution - Histogram
3. Employee Man-Hours Analysis - Box Plot
4. Annual Reporting Trends - Line Chart
5. Operational Correlation - Scatter Plot

#### **Interactive Visualizations (8)**
- Geographic injury heatmaps
- Time-series trend analyzers
- Railroad performance dashboards
- Safety metric correlation explorers
- Hierarchical data sunburst charts
- Comparative analysis tools

## 🔑 Major Insights Discovered

### **Operational Patterns**
- **Reporting Disparities:** Significant variation in injury reporting frequency across railroads
- **Seasonal Trends:** Observable patterns in incident occurrence throughout the year
- **Geographic Concentrations:** Specific regions show higher incident rates

### **Safety Performance**
- **Railroad Classification:** Different railroad types exhibit distinct safety profiles
- **Mileage-Injury Correlations:** Relationships between operational volume and incident frequency
- **Reporting Compliance:** Variability in data completeness and quality

### **Data Quality Observations**
- **Missing Data Challenges:** Some fields (Narrative, Railroad Type) have high missing rates
- **Formatting Issues:** Numeric data stored as strings with special characters
- **Consistency:** Standardization needed across reporting entities

## 💼 Business Applications

### **Safety Management**
- Identify high-risk operations for targeted interventions
- Benchmark safety performance across the industry
- Monitor compliance with OSHA reporting requirements

### **Operational Optimization**
- Correlate safety incidents with operational metrics
- Identify efficiency-safety trade-offs
- Support resource allocation decisions

### **Strategic Planning**
- Inform policy development with data-driven insights
- Support risk assessment and mitigation strategies
- Guide investment in safety infrastructure

## 📈 Project Outputs
- **Cleaned Dataset:** Ready for further analysis
- **Comprehensive Visualizations:** Both static and interactive formats
- **Documented Analysis:** Transparent, reproducible methodology
- **Actionable Recommendations:** Business-focused insights

## 🚀 Getting Started

### **Prerequisites**
- Python 3.7+
- Jupyter Notebook environment
- Required Python libraries (see requirements.txt)

### **Setup Instructions**
```bash
# Clone repository
git clone https://github.com/yourusername/osha-safety-analysis.git

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook Task1.ipynb
```

### **Data Access**
- Download OSHA dataset from the provided link
- Place `OSHA_Injury_Illness_2023.csv` in project directory
- Follow notebook prompts for data upload

## 📚 Documentation Structure
- **Code Documentation:** Inline comments explaining each step
- **Analysis Rationale:** Justification for methodological choices
- **Result Interpretation:** Clear explanations of findings
- **Business Context:** Translation of insights into actionable intelligence

## 🤝 Contribution & Collaboration
This project serves as a template for:
- **Data Science Practitioners:** EDA methodology reference
- **Safety Analysts:** Railroad industry safety analysis framework
- **Business Intelligence:** Operational data analysis approach
- **Academic Research:** Public safety data analysis case study

## 📄 License & Attribution
- **Data Source:** U.S. Government Open Data
- **Code:** Open-source for educational and analytical purposes
- **Attribution:** Please cite when using this analysis framework

## 📬 Contact & Support
For questions, suggestions, or collaboration opportunities:
- GitHub Issues: Report bugs or request features
- Email: [Your Contact Information]
- LinkedIn: [Your Professional Profile]

