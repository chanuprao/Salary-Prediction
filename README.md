# What is this project about ?

This is a salary prediction model using statistical regression techniques.

# Elements 

- Python Language
- Statistical knowledge
- Data Analysis
- Results Interpretation

# Data Used

Data used for this project has salary and a few other attributes which are used to build a model to predict the salary variable.
From the available attributes, only below variables were used for this model building exercise:

* Years Experience: How many years of experience
* Job Type: The position held (CEO, CFO, CTO, Vice President, Manager, Janitor, and senior or junior position)
* College Degree: Doctoral, Masters, Bachelors, High School, or None
* College Major: Biology, Business, Chemistry, Computer Science, Engineering, Literature, Math, Physics, or None
* Industry: Auto, Education, Finance, Health, Oil, Service, or Web
* Miles From Metropolis: How many miles away from a major city

# Process

After an exploratory data analysis exercise, data was cleaned.
Three different techniques were tried to get a decent model and the results are captured in the attached python notebook.

# What is a decent model ?

Now as the answer to this question might vary drastically depending on use cases, In our use case we are aiming at MSE below 320.
MSE, is the Mean Sqaured error which is the mean of the sqaured differences of the actual and predicted values.
This is a good metric to measure the performance of a predictive model.

# Summary

Feature engineering and transforming the input variables to the polynomial features of 2nd degree, helped us to get a good model with MSE ~ 308 and model accuracy at 78%.
We were also able to interpret the results and find some co-relations between the target and input variables which are discussed in the notebook !!

# Thank You !
