# Heston Option Pricing
This repository includes the code and the report for the final project of the course of _Machine Learning for finance_ FIN-418 EPFL.
course webpage: https://edu.epfl.ch/coursebook/en/machine-learning-for-finance-FIN-418

Abstract:
The Heston model, thanks to its closed-form solution, allows to easily price European call options. This model-based solution is our benchmark to compare the performances of different pricers. We use the Monte Carlo method, also applying a variance reduction technique. Next, we focus on ML models by proposing to combine classification and regression, because this allows to obtain good results through relatively simple methods. In conclusion, we present a solution to improve the results in the ATM region, which is the hardest one to predict. This combination idea, being model-independent and particularly flexible, aims to be a good answer in many situations, not only for the Heston model.

Structure of the code:
- Explicit solution of the Heston price equation (functions)
- Stock paths generator (functions)
- Generate data
- Monte Carlo simulation
    - Monte Carlo simulation with Antithetic variables
    - Time analysis of Monte Cralo
    - Effects in changing number of simulations in Monte Carlo
    - Error analysis Monte Carlo
- ML methods
    - Motivation in combining regression and classification
    - Classification
    - Regression
- ATM area
- Change Datasets

