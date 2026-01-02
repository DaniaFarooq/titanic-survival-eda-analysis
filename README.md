# Titanic Survival - Exploratory Data Analysis

## 📊 Project Overview
A comprehensive exploratory data analysis of the Titanic passenger dataset to identify key factors influencing survival rates.

**Live Demo**: [View the HTML export](titanic_analysis.html)

## 🎯 Objectives
- Perform univariate and multivariate analysis of passenger data
- Identify demographic and socio-economic factors affecting survival
- Create insightful visualizations to communicate findings
- Derive actionable insights from historical data

## 📁 Dataset
- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)
- **Records**: 887 passengers
- **Features**: 8 original columns
- **Target Variable**: `Survived` (0 = No, 1 = Yes)

## 🛠️ Technologies Used
- **Python 3.9+**
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Notebook**: Jupyter
- **Version Control**: Git, GitHub

## 📈 Key Insights

### 🔍 Survival Factors Identified:
1. **Gender**: Females had 68.1% survival rate vs males at 31.9%
2. **Passenger Class**: 1st class (63%) > 2nd class (47%) > 3rd class (24%)
3. **Age**: Children (<12) had highest survival (50%), seniors lowest (19.2%)
4. **Family Size**: Traveling with family (50.6%) > traveling alone (30.6%)
5. **Fare**: Higher fare correlated with better survival chances

### 📊 Key Statistics:
- Overall survival rate: **38.6%**
- Most common passenger class: **3rd (55%)**
- Gender ratio: **65% male, 35% female**
- Average age: **29.5 years**
  
## 📁 Project Structure

titanic-survival-eda-analysis/

├── titanic_analysis.ipynb  (Main analysis notebook)

├── titanic_analysis.html  (Static HTML export)

├── requirements.txt  (Python dependencies)

├── data/  (Raw and processed data)

├── images/  (All visualizations)

## Run the Analysis
1. Clone this repository:

   git clone https://github.com/DaniaFarooq/titanic-survival-eda-analysis.git

   cd titanic-survival-eda-analysis

2. Launch Jupyter Notebook:

   jupyter notebook titanic_analysis.ipynb

3. Or view the HTML export directly:

   Open [titanic_analysis.html](titanic_analysis.html) in any browser

## 📝 Analysis Process
**Data Loading & Inspection** - Initial data quality assessment

**Data Preprocessing** - Type conversion, missing value handling

**Univariate Analysis** - Distribution analysis of individual features

**Multivariate Analysis** - Relationship exploration between features

**Feature Engineering** - Creating new meaningful features

**Insights & Conclusions** - Key findings and recommendations

## 🔮 Future Enhancements
Build predictive models (Logistic Regression, Random Forest)

Implement machine learning pipelines

Create interactive dashboard with Plotly Dash

Deploy as a web application

## Author
> EDA done by **Dania Farooq**  
- [LinkedIn](https://www.linkedin.com/in/daniafarooq/)

## 📩 Feedback & Collaboration

Feel free to:  
- ⭐ Star this repo if you find it helpful  
- 🛠 Suggest improvements via [Issues](https://github.com/DaniaFarooq)  
- 📥 Contribute through Pull Requests  

## License
This project is licensed under the MIT License - see the LICENSE file for details.
