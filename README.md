# Interaction-of-ad-medias-on-sales
Linear Regression model to demonstrate how different medias interact to impact sales.  
  
Two linear regression models are ran:  
1. Without interaction between different medias(Facebook, Youtube and Newspaper)  
2. With interaction ( Facebook and Youtube and Youtube and Newspaper)   
This effect is called Synergy - Synergy in marketing is when two marketing initiatives create a response greater than the sum of the combined response the two would have elicited alone.    
  
Model assesment:  
1. Adjusted R2 is greater for model2 with interaction. Adjusted R2 represents percentage of variation in response variable explained by predictor variable.
2. Standard error: Lower the standard error, better the model. Model with interaction has lower standard error.  
3. t-value means what is the standard error in the coefficient. A large t-value, relative to standard error, would provide evidence against the null hypothesis and indicate that a relationships exists between the independent and dependent variable. Predictors with low t-statistics can be dropped. Ideally, the t-value should be greater than 1.96 for a p-value to be less than 0.05.  
4.P-value should be less than 0.05. Pr(>t) represents the p-value or the probability of observing a value larger than t.
5. AIC, BIC is also low for second model with interaction.
6. The F-test of overall significance indicates whether your linear regression model provides a better fit to the data than a model that contains no independent variables. The greater the F-value the better. We see that model with interaction has greater overall F-value.  
