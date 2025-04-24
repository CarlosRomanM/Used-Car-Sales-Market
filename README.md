# Used-Car-Sales-Market


## Introduction to Regression

Regression is a statistical technique used to model the relationship between a dependent variable 
(in this case, the car price) and one or more independent variables (such as mileage, horsepower 
(HP), age, and type of transmission). It is a key tool in data analysis, enabling the prediction 
of future values based on patterns identified
in historical data.


In this project, we will explore different models ranging from simpler to more complex ones. 
I will demonstrate which model is more effective, along with their advantages and disadvantages 
depending on their use and the problem at hand. This will allow us to visually and practically 
observe how each model behaves and which one can be more easily adapted to our questions.


## Model Comparison

-R² as a Key Metric: More complex models (multiple regression) have a significantly higher R², indicating that they 
better explain the variability in the price.

-Error Distribution: More complex models also show a narrower and more centered error distribution, suggesting 
greater accuracy in predictions.

-Simplicity vs. Complexity: While simple models are easier to interpret, multiple and polynomial models are more
effective in capturing the complexity of the data.


## Final Conclusions:

- Importance of Variables: Car prices are influenced by multiple factors, and a model that considers only one variable
(such as mileage or age) is insufficient to capture the market's complexity.

- Multiple Models as the Best Option: Multiple regression models are the most suitable for predicting prices as they 
integrate various vehicle characteristics that affect their value.

- Nonlinear Relationships: Including polynomial terms (like Age²) improves the model's fit by capturing nonlinear 
relationships, such as the accelerated depreciation of older vehicles.

- Practical Applications: The final model can be used to estimate car prices based on their features, making it a 
valuable tool for dealerships, buyers, and sellers in the used car market.

- Limitations: While the models explain much of the variability, external factors (such as market conditions or 
economic events) remain that cannot be fully captured.

- In summary, the analysis demonstrates that multiple regression models, combined with polynomial terms when necessary, 
are powerful tools for predicting car prices. However, it is crucial to validate these models with additional data and 
consider external factors to further improve their accuracy.


## Requirements
To install the necessary dependencies, use the following command:
pip install -r requirements.txt


## Execution
To run the scan, open the file `notebooks/sales_auto2.ipynb`.

## License
This project is licensed under the [MIT License](LICENSE).
