# 🎓 Graduate Admissions Predictor

## 📖 Project Overview

This project analyzes the factors influencing graduate admissions and predicts the probability of admission to Ivy League colleges for students from India. Using data from various parameters like GRE scores, TOEFL scores, and research experience, the model offers valuable insights into the admissions process.

## 📊 Dataset

- **Dataset Link**: [jamboree_admission.csv](https://drive.google.com/file/d/11bT-ezOT8vkD3WPSIGwwiDeUX4-rP1cF/view?usp=sharing) 
  
### Column Description:
- **Serial No.**: Unique row ID
- **GRE Scores**: Out of 340
- **TOEFL Scores**: Out of 120
- **University Rating**: Out of 5
- **SOP/LOR Strength**: Out of 5
- **Undergraduate GPA**: Out of 10
- **Research Experience**: Binary (0 or 1)
- **Chance of Admit**: Ranges from 0 to 1

## 🧠 Key Concepts

- **Exploratory Data Analysis**: Understanding data patterns and relationships.
- **Feature Engineering**: Creating new features or modifying existing ones to improve model performance.
- **Linear Regression**: Predictive modeling to estimate chances of admission.

## 🔍 Analysis and Findings

1. **Exploratory Data Analysis (EDA)**:
   - Investigated the structure of the dataset and identified key variables.
   - Visualized data distributions and relationships between variables.
   - Checked for correlations to understand interdependencies.

2. **Model Building**:
   - Built a Linear Regression model using the Statsmodel library.
   - Tested assumptions: 
     - Multicollinearity using VIF scores
     - Normality of residuals
     - Homoscedasticity
   - Evaluated model performance using MAE, RMSE, R², and Adjusted R² metrics.

3. **Actionable Insights**:
   - Identified significant predictor variables for graduate admissions.
   - Recommendations for improving admission chances based on analyzed data.

## 📝 Conclusion

This project demonstrates a comprehensive approach to analyzing and predicting graduate admissions, providing valuable insights for prospective students. The methodology and findings can help guide students in enhancing their profiles to improve their chances of admission.

## 💡 Future Work

- Explore advanced modeling techniques such as Ridge and Lasso regression.
- Incorporate additional data sources for enhanced model accuracy.
- Implement the model in real-world applications to assist students in understanding their admission probabilities.

## 📧 Contact

For further information or collaboration, please feel free to reach out:

- **Email**: adharshreddy.c@gmail.com
- **LinkedIn**: [ adharshreddyc](https://www.linkedin.com/in/adharshreddyc/)
