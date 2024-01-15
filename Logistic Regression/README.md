# Logistic Regression

Logistic regression is a statistical method used for modeling the probability of a binary outcome. Unlike linear regression, which predicts a continuous variable, logistic regression is employed when the dependent variable is categorical and has two possible outcomes, typically coded as 0 and 1. The logistic regression model applies the logistic function to transform a linear combination of predictor variables into a range between 0 and 1. The logistic regression equation is expressed as:

```plaintext
p(y=1) = 1 / (1 + e^-(β₀ + β₁x₁ + β₂x₂ + ... + βₖxₖ))
