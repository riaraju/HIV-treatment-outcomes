# HIV Data Analysis Project

This project aims to assess long-term treatment outcomes in HIV-positive patients by analyzing various factors such as demographics, ART regimens, and clinical stages. The study explores correlations between these factors and key clinical metrics like viral load progression, opportunistic infections, CD4 count, and adherence to antiretroviral therapy (ART).

## Project Overview

In countries where ART is widely accessible, HIV has transitioned from a fatal disease to a manageable chronic condition. However, challenges like adherence to therapy, opportunistic infections, and quality of life persist. This project uses data-driven approaches to uncover patterns and provide insights for improving treatment outcomes.

### Key Features
- **Data Cleaning**: Addressed missing values, duplicates, and outliers for accurate analysis.
- **Data Analysis**: Applied statistical methods to identify relationships and trends in HIV patient data.
- **Machine Learning**:
  - **Classification Models**: Analyzed treatment adherence and opportunistic infections, achieving strong performance with Gradient Boosting and 0.79 accuracy with Decision Tree Classifier.
  - **Regression Models**: Predicted CD4 count and viral load using regression techniques, with stacked models outperforming individual regressors.
- **Visualization**: Created insightful visualizations (density plots, bar charts, violin plots) to highlight trends and findings.

## Dataset

The dataset used in this project was sourced from [Kaggle](https://www.kaggle.com/datasets/iogbonna/quality-of-care-dataset-for-hiv-clients) and contains 27,289 rows and 46 attributes. Key attributes include:
- **Independent Variables**: Age, sex, marital status, education, occupation, regimen type, weight, and clinical stage.
- **Dependent Variables**: Opportunistic infection, viral load, most recent CD4 count, and ART adherence.

## Methodology

1. **Data Preprocessing**:
   - Handled missing data using imputation.
   - Removed duplicates and addressed outliers using interquartile range (IQR) methods.
   - Converted categorical variables to numerical formats.

2. **Exploratory Data Analysis (EDA)**:
   - Conducted statistical tests (Mann-Whitney, Kruskal-Wallis, Chi-Square) to evaluate associations.
   - Correlation analysis to uncover relationships between variables.

3. **Machine Learning**:
   - Built classification models for categorical outcomes.
   - Used regression models for continuous outcomes.
   - Applied stacking models for improved predictive accuracy.

4. **Visualization**:
   - Visualized relationships using density plots, bar charts, violin plots, and more.

## Results

- **Classification Models**: Gradient Boosting outperformed others for categorical predictions, with 0.79 accuracy using the Decision Tree Classifier.
- **Regression Models**: Stacked models provided the best performance for predicting CD4 count and viral load, outperforming individual models like Gradient Boosting.

## Tools and Technologies

- **Programming Languages**: Python, SQL
- **Libraries**: Pandas, NumPy, Matplotlib, Scikit-learn
- **Database Management**: MySQL (via phpMyAdmin)
- **Environment**: Jupyter Notebook

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/HIV-Data-Analysis.git
