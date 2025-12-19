# Consumer Behavior Predictor

A Data Mining project utilizing Python to build and evaluate Decision Tree, Random Forest, and Gradient Boosting models. This analysis focuses on predictive classification using the scikit-learn and dmba libraries.

## Project Overview 
The goal of this project was to utilize ensemble learning techniques, specifically Gradient Boosting, to identify the key demographic drivers of consumer behavior. By analyzing feature importance, I determined that Income and Education were the primary predictors, allowing for a model with over 98% classification accuracy. This analysis applies data mining techniques to predict consumer ownership patterns by building and comparing multiple classification models to identify the most effective predictive methods.
 
## Key Features

**Predictive Classification**: Implemented Decision Trees to categorize ownership based on demographic variables.

**Ensemble Learning**: Evaluated advanced models including Random Forest and Gradient Boosting to optimize performance.

**Statistical Evaluation**: Used classification summaries and accuracy metrics to validate model reliability.

**Model Visualization**: Generated visual tree diagrams to interpret complex decision-making paths.

## Key Findings & Model Results

**Primary Predictor**: Through decision tree analysis, Income was identified as the most critical feature in determining ownership, with the initial split occurring at the **$59,700** threshold.

**High Training Accuracy**: The fully grown Decision Tree achieved a perfect **1.0000 Accuracy** on the training dataset, correctly classifying all 19 samples.

**Strong Validation Performance**: On unseen data (validation set), the model maintained a **98% Accuracy** rate.

**Classification Balance**: The model correctly identified 100% of the "Owners" in the validation set, though it had a slight tendency to misclassify one "Nonowner" as an "Owner".

## Business Impact

The model's ability to achieve 100% recall for the "Owner" class carries significant practical value for targeted marketing strategies:

**Zero Missed Opportunities**: By correctly identifying every actual owner in the validation set, the business ensures that no potential high-value customers are overlooked during a campaign.

**Optimized Marketing Spend**: While the model has a slight tendency to misclassify one "Nonowner" as an "Owner" (a False Positive), this is a low-risk error. It is generally more cost-effective to send an extra marketing communication than to miss a guaranteed conversion.

**Actionable Customer Profiling**: Identifying Income (with a $59,700 threshold) and Education as the primary drivers allows management to refine their customer personas and focus resources on the most profitable segments.

## Visualizations

### Decision Tree Analysis
Below is the visualization of the primary Decision Tree used in this project. It highlights how the model utilizes **Income** and **Lot Size** to categorize ownership.

![Decision Tree Visualization](Decision_Tree.Png)

### Feature Importance
This plot ranks the demographic drivers of consumer behavior, identifying **Income** as the most significant predictor.

![Feature Importance Plot](Feature%20Important%20Plot.Png)


## Technologies Used
 
**Programming**: Python

**Machine Learning**: scikit-learn

**Specialized Analytics**: dmba (Data Mining for Business Analytics)

**Data Handling**: Pandas

