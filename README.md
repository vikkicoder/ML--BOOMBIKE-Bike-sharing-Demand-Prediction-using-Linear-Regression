# Bike Sharing Demand Analysis using ML Multi Linear Regression
 
by 

Vishnu Vardhan Gudla

# Objective

Build a multiple linear regression model for the prediction of demand for shared bikes

# Problem Statement
 
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario.

> So, it has decided to come up with a mindful business plan to be able to accelerate its revenue by understanding the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

The company wants to know:

> Which variables are significant in predicting the demand for shared bikes.

> How well those variables describe the bike demands

They have contracted a consulting company to understand the factors affecting the demand for these shared bikes in the American market.

# Bike Sharing Demand Analysis Outline:
1. Reading, understanding and visualizing the data (EDA)

2. Preparing the data for model training (train-test split, rescaling)

3. Training the model (Model building, Feature Selection (RFE+Manual))

4. Residual analysis

5. Prediction and evaluation of the test set


# The equation of the best fitted line is giveny by:

count=0.144614+0.233312×year+0.055438×workingday+0.470719×temperature−0.111605×spring+0.056603×winter+−0.065787×july+0.062275×september+0.063954×Monday−0.304382×lightsnow/rain−0.080935×mist/cloudy

# inference:

The variance in the target varaible count can be explained majorly by

>Temperature (+0.470719)

>Year (+0.233312)

>Light snow + Rain (-0.304382)


## Technologies Used
- Numpy 
- Pandas 
- Matplotlib 
- Seaborn 
- SKlearn
- Statsmodels





## Contact
Created by [@vikkicoder] - feel free to contact me!

