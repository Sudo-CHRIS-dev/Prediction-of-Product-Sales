# Prediction of Product Sales
## Using machine learning to predict product sales

- **Author: Christian Bam**
- 
### Business problem:

- **The bussiness problem was to identify and predict sales of products**
- **To identify and explain correlating aspects which play a role in product sales**

### Data:
https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view?usp=sharing

 1   Item Weight                
 2   Item Fat Content          
 3   Item Visibility           
 4   Item Type               
 5   Item MRP                   
 6   Outlet Identifier          
 7   Outlet Establishment Year   
 8   Outlet Size                 
 9   Outlet Location Type       
 10  Outlet Type                
 11  Item Outlet Sale


## Methods
* Clean data 
  - Check for duplicates and drop thme.
  - Identify and Impute missing values
  - Find and fix any inconsistent categories of data
* Exploratory Data Analysis
  - Histograms to view the distributions of numerical features in your dataset.
  - Boxplots to view statistical summaries of numerical features in your dataset.
  - Countplots to view the frequency of each class of categorial features in your dataset.
  - Heatmap to view the correlation between features.
* Explanatory Data Analysis
  - Create a univariate visualization showing the distribution of values/categories.
  - Create a multivariate visualization plotting each feature vs. the target.
* Building Machine learning piplines and transforming data
* Using Machine learning to predict sales
  - build a linear regression model
  - Random Forest model
  - GridSearchCV to tune at least two hyperparameters 


## Results

#### Item_MRP vs. Item_Outlet_Sales
![Item_MRP vs. Item_Outlet_Sales]((https://github.com/Sudo-CHRIS-dev/Prediction-of-Product-Sales/assets/122632203/16ddbb49-b0f5-46a8-9c3f-ad5ff00707a0)

> This graph show us that the higher the max retail price the more sales

#### most popular supermarket

![OutletTypeAmount](https://github.com/Sudo-CHRIS-dev/Prediction-of-Product-Sales/assets/122632203/5fedfd11-a433-416e-a542-1c5cdbf7f4fc)

> This graph shows us that the most popular supermarket is type one which means that those types of supermarkets are successful

## Model

A Random Forest model was used along with GridSearchCV

- MAE = 736.591
- MSE = 1,114,175.672
- RMSE = 1,055.545
- R^2 = 0.602

The R2 score explains the variance of a target. As per our metrics we can see that their is a relatively good fit as shown by the R2 value.
Root Mean Squared Error penalizes Large Errors, as seen in my metrics there are a few large errors, I am using this metric as I belive large 
errors should be punished, but want my units of measure the Same as the target. As we can see by the total score the amount of errors are 
relatively low all things considered.


### For further information


For any additional questions, please contact **Christianmatthewbam@gmail.com**
