# Using ML to predict weather

A predictive model to forcast the maximum temperature for the next day.  I started by collecting and cleaning the data, followed by an in-depth analysis to gain insights into the underlying patterns. Using a machine learning algorithm, I trained a model that achieved promising results. To further enhance its accuracy, I implemented feature engineering techniques and conducted rigorous testing and evaluation.


### Download Data
- dowmloaded data from https://www.ncei.noaa.gov/cdo-web/
- data collected by Chicago Ohare Airport
### Data Cleaning
- used only the "core weather" indicators: precipication, snow depth, temp max, temp min
- remove invalid values using forward fill and replace by zero
- verify correct data types
- convert to pandas datetime index
### Analyzing Data
- plot data to view relationship between predictors
### Machine Learning
- implement Ridge model
- split data into training and testing data
- identify features
- evaluate model with MSE
### Evaluate the model 
- plot the predicted vs acutal temps
- wrap model and evaluating into a function
### Improving the model
- create new features by:
  - comparing monthly max temp and daily max temp, max temp and min temp
  - creating rolling average of montly and yearly temps
### Running Model Diagnostics
- analyze the regression coeffients
- analyze correlation coefficents between features
- analyze most innacurate predictions
