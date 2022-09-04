# Real-Estate-House-Price-Prediction

- Backend :
Features - 

Property price prediction with the help of maintenance approach
According to the Research paper - Housing Price Prediction using ML 
Journal - IRJET(International Research Journal of Engineering and Technology)
ISSN - 2395 0056. 

The real estate market is one of the fields where machine learning can be applied to optimize and predict the price with high accuracy. Determining housing price is a vital model for decision making for customers in which a number of parameters can be considered to predict the price of a desired house.

Proposed System ArchitectureAs discussed above, architecture does not have the accurate price prediction to overcome this we designed architecture where accuracy can be achieved.


- As per Survey :

In 2018, Rohan Bafna, Anirudh Dhole, Ankit Jagtap, Asif Kazi, Arbaz Kazi specified the rate of fluctuation in prices should have a method for its traceability.
The Hedonic pricing model joins both a house’s internal characteristics (such as number of bedrooms, Number of restrooms, etc.) and its external characteristics (such as neighborhood walkability score, schools’ scores, etc.)
In 2016 Kanojia Anita specified the hedonic pricing method is relatively straightforward and uncontroversial to apply, because it is based on actual market prices and fairly easily measured data. If data is readily available, it can be relatively inexpensive to apply. If data must be gathered and compiled, the cost of an application can increase substantially.
This existing system as we saw includes the use of classifiers where they train the dataset and perform operations on the dataset and then the user gets output value.
This system works on classifier and its repetitive output since predicting accurate house prices is not possible with this architecture.





- HOW IS THIS DIFFERENT?

Uniqueness plays an important role in any new pitch. Other property dealing services provide a platform for the buyers as well as the sellers to locate properties of interest. But this price prediction is the predicted price of the property listed to the company by its employees from the sellers and keeping in view the tax and maintenance of the property depending upon the requirements of the buyer.


- WHY ML?

-Real estate prices never remain constant.
-If any manual database or filter is used to give this information to the users, this will be time taking and inaccurate while ML can reach these updated data in no time.


- Benefits of Data Science in Real Estate :

1.) Reduces Risks: with the help of predictive analytics companies can use it to estimate the overall condition like its ages, deconstruction history, owner information. the company can provide their customers with up-to-date information so it increases their satisfaction from working with them.

2.) It helps calculate the price: precise cost calculation in real estate is time-consuming, how the Machine learning algorithm can use for the estimate the price of properties with the help of historical data.

3.) Data-driven decision: Machine learning opens many opportunities for the business. just feed the algorithm with data and it will process it to help you make the right decision.

4.) Marketing strategy: with the help of customer information companies can plan their future marketing strategy according to customer needs.

American online real estate database company zillow has used data science in the real estate market. Zillow determines an estimate, also known as a zestimate for a house, based on a range of publicly available information, including sales of comparable houses in a neighborhood.


- ML Methods and technique used :

Three different types of Machine Learning methods including Random Forest, XGBoost, and LightGBM.
(LightGBM is a gradient boosting framework that uses a tree-based learning algorithm. LightGBM has faster train- ing speed with lower memory usage compare to XGBoost) 
XGBoost is a scalable machine learning system for tree boosting. When the model performed with a high accuracy with RMSLE(Root Mean Squared Logarithmic error) of the training set then there is the chance to get the actual price.
Random Forest is a kind of ensemble model that combines the prediction of multiple decision trees to create a more accurate final prediction. We used the RandomForestClassifier class provided by sklearn. The RandomForestClassifier has a n_estimators parameter that allows to indicate how many trees to build,


- Two techniques in machine learning including Hybrid Regression and Stacked Generalization Regression are compared and analyzed for optimal solutions.
ALGORITHM USED :

- We will mainly use K-fold Cross Validation and GridSearchCV technique to perform hyper parameter tuning to obtain the best algorithm and parameters for the model
