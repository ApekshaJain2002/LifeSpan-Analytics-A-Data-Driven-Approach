# LifeSpan Analytics: A Data-Driven Approach

## Overview
"LifeSpan Analytics: A Data-Driven Approach" is a comprehensive project aimed at analyzing and predicting life expectancy for countries worldwide. Using health, economic, and social factors from 193 countries over the period of 2000-2015, this project identifies the key contributors to life expectancy and employs machine learning techniques to predict outcomes based on these factors.

## Project Motivation
Life expectancy is a critical indicator of a population's health and well-being. This project goes beyond traditional predictors by incorporating factors such as immunization, mortality rates, and economic metrics. By analyzing these factors, the goal is to provide actionable insights for policymakers and public health officials, helping to improve life expectancy across different regions.

## Key Features
- **Data Collection**: Data is sourced from the World Health Organization (WHO) and United Nations, covering health, economic, and demographic indicators.
- **Analysis**:
  - Birth Rate
  - Health Expenditure
  - Gross Domestic Product (GDP)
  - Immunization Coverage (Polio, Hepatitis B, Diphtheria)
  - Adult and Infant Mortality Rates
  - Schooling and BMI
  - HIV/AIDS-related Deaths
  - Population-related metrics
- **Objective**: Predict life expectancy using machine learning models based on these factors.

## Methodology
The project follows a structured approach:
1. **Data Cleaning**: Initial handling of missing values, outlier detection, and data imputation.
2. **Exploratory Data Analysis (EDA)**: Visualization of data distribution, correlations between features, and statistical insights.
3. **Feature Engineering**: Selection of relevant features based on statistical relationships with life expectancy.
4. **Modeling**: Several machine learning models were tested:
   - **Linear Regression**
   - **Ridge Regression**
   - **Lasso Regression**
   - **Polynomial Regression**
   - **Gradient Boosting Regression**
5. **Model Evaluation**: Models were evaluated based on performance metrics such as accuracy, with **Gradient Boosting** providing the best results.

## Tools and Technologies
- **Programming Language**: Python
- **Libraries**:
  - Pandas and NumPy for data manipulation
  - Matplotlib and Seaborn for visualizations
  - Scikit-learn for model implementation
- **Machine Learning Models**: Gradient Boosting, Lasso, Ridge, Linear Regression

## Results
- **Best Model**: Gradient Boosting Regression with an accuracy of over 95%.
- **Key Predictors**:
  - **Income Composition**: Strong correlation with life expectancy.
  - **Adult Mortality Rates**: Significant predictor of life span.
  - **Schooling and Education**: Strong positive correlation with life expectancy.
  - **HIV/AIDS Death Rates**: Negative impact on life expectancy.
  - **Thinness among children and adolescents**: Critical factor in developing countries.
  
Life expectancy was found to vary significantly between developed and developing countries, with wealthier nations having higher averages.

## Conclusion
The project concludes that public health interventions, such as improving education, addressing child malnutrition, and increasing access to healthcare, have a significant impact on life expectancy. These insights can guide countries in their efforts to improve population health outcomes.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/lifespan-analytics.git
   ```
2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis:
   Open the `life_expectancy_analysis.ipynb` Jupyter Notebook file to run the project in your preferred environment.

## File Structure
- `life_expectancy_analysis.ipynb` - Jupyter notebook containing all steps of the analysis.
- `dataset.csv` - Data used for the analysis (optional: provide a link to the data).
- `requirements.txt` - List of required Python packages.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## References
- World Health Organization (WHO)
- United Nations Data
- Scikit-learn Documentation
- [Articles on life expectancy](https://towardsdatascience.com/what-really-drives-higher-life-expectancy-e1c1ec22f6e1)
- ![image](https://github.com/user-attachments/assets/21b2b65b-4d69-4c10-a81d-f436be09d3f9)

