# HousingSalePricePredictor
Predicting Housing Final Sale Price of a set of data from 2006 to 2010 using Cross-validation.

This program is run on Google Colab with the dataset housing_price_full_sample being stored on your own Google Drive. Before running the program, adjust the directories in the first code block to your own.

Here's a summary based on the paper and code for your GitHub README:

### Overview
This project explores machine learning techniques to predict housing prices using a dataset of residential sales in Ames, Iowa (2006-2010). Utilizing multiple linear regression and focusing on Mean Squared Error (MSE) and R-squared as performance metrics, the study compares two models for accuracy in predicting housing prices.

### Models
1. **Model 1**: Uses the nine variables most correlated with the sale price. After evaluating p-values and correlation, six key predictors remained: Ground Living Area, Overall Quality, Total Rooms Above Ground, Garage Capacity, Total Basement Area, and Masonry Veneer Area.
2. **Model 2**: Built with all 389 variables, refined to 43 significant predictors by systematically removing those with high p-values.

### Results
- **Model 1** has lower MSE, indicating better predictive accuracy for unseen data.
- **Model 2** has a higher R-squared, suggesting a stronger fit but a higher tendency to overfit.
  
The models highlight key factors influencing housing prices, such as overall quality and living area. However, multicollinearity led to exclusions of some significant variables, pointing to potential improvements.

### Conclusion
While Model 2 showed a better overall fit, Model 1 excelled in predictive accuracy. This project underscores the trade-offs in model complexity and calls for future improvements in handling multicollinearity to enhance prediction accuracy.
