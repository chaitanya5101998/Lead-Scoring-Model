# Lead Scoring Analysis for X Education

## Project Overview

The objective of this project is to analyze factors influencing lead conversion for X Education, develop strategies to optimize lead conversion efforts, and present the findings in a detailed report and presentation. The primary goals are to:
1. Identify key variables affecting lead conversion.
2. Determine the most important categorical/dummy variables.
3. Recommend business strategies for different operational phases.

## Data Understanding and Preparation

### Data Quality Checks
1. **Missing Values**: Missing values were imputed with appropriate defaults (e.g., mean for numerical columns).
2. **Categorical Variables**: Categorical variables were converted to dummy variables using one-hot encoding.
3. **Data Cleaning**: The dataset was cleaned and converted to a format suitable for analysis in Python.

### Exploratory Data Analysis (EDA)
EDA was performed to understand the distribution and relationships of the data. Key insights were derived from visualizations and summary statistics.

## Model Building and Evaluation

### Model Selection
A RandomForestClassifier was chosen for its robustness and ability to handle a mix of numerical and categorical data. The dataset was split into training and testing sets to evaluate the model's performance.

### Feature Importance
Feature importance was extracted from the RandomForestClassifier to identify the variables most significantly impacting lead conversion. The top three variables were:
1. Total Time Spent on Website
2. Lead Source_Welingak Website
3. Lead Origin_Landing Page Submission

### Model Evaluation
The model's performance was evaluated using the ROC curve and feature importance analysis. The results were satisfactory, aligning with the best possible outcomes on the dataset.

## Business Strategies

### Aggressive Lead Conversion During Intern Phases
1. Prioritize high-probability leads.
2. Segment and allocate leads among interns.
3. Continuously monitor and adjust lead conversion rates.

### Minimizing Unnecessary Phone Calls After Meeting Targets
1. Set a higher threshold for lead scores.
2. Use automated filtering to remove lower probability leads.
3. Allocate the sales team to focus on other tasks once targets are met.

## Visualizations

### Feature Importance Plot
A bar plot showing the top features contributing to lead conversion.

### ROC Curve
A plot displaying the Receiver Operating Characteristic (ROC) curve, illustrating the model's performance in distinguishing between converted and non-converted leads.

## Summary and Key Takeaways

1. **Data Preprocessing**: Ensuring data completeness and accuracy is crucial for reliable model performance.
2. **Model Selection and Evaluation**: Choosing the right model and properly evaluating its performance significantly impacts the quality of insights.
3. **Feature Importance**: Understanding which variables most influence lead conversion guides strategic business decisions.
4. **Visualization**: Effective visualizations are essential for communicating complex findings.
5. **Strategic Recommendations**: Translating analytical findings into actionable business strategies delivers value from data analysis.

## Learnings

- The importance of thorough data preprocessing.
- The impact of model selection and evaluation techniques.
- The significance of feature importance in driving business decisions.
- The role of visualizations in effectively communicating insights.
- The need for actionable business strategies based on analytical findings.

## Files in Repository

- `Lead_Scoring_Analysis.ipynb`: Jupyter notebook containing the analysis and model building process.
- `Lead_Scoring_Analysis_Presentation.pdf`: Presentation summarizing the findings and recommendations.
- `Summary Report.pdf`: Detailed report outlining the process, findings, and strategies.
- `Assignment_Solutions_Completed.pdf`: Solutions to assignment questions related to the analysis.
