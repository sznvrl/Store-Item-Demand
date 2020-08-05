# Store-Item-Demand


### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Problem Definition](#problem)
4. [File Descriptions](#files)
5. [Results](#results)

## Installation <a name="installation"></a>

Python 3.0 used for all analysis. Pandas, numpy, matplotlib, seaborn, matplotlib, plotly.express, plotly.figure_factory, plotly.graph_objs, plotly.offline,datetime and pyplot  were used.

## Project Motivation<a name="motivation"></a>

In this paper, we focused on store item demand forecasting. For efficient warehouse management first step is ensure to stock control. Therefore, production planning plays critical role. The way to successful planning depends on classifying and analyzing materials. Many companies use different classification or forecasting methods for material/production planning.



## Problem Definition<a name="problem"></a>

Our problem is to make the most accurate demand forecasting and manage the inventory planning process correctly. Thus, unnecessary costs will not be tolerated. Customer demands will be met instantly, we will not lose potential customers. When we look at our data, the issue we want to solve is to find the right product in the right store at the right time.


## File Descriptions <a name="files"></a>
"Store Item Demand Forecasting” dataset was used from Kaggle platform. There is store item sales between 2013 and 2017. There are 50 different items. Total sales are available daily. 

Files:

train.csv : Train data set
test.csv : Test data set
sample_submission.csv: Sample submission file

Columns:

date: date of sales
Store: store id
item: item id
sales: number of sales



## Results<a name="results"></a>
In the analyze, Random Forest regressor used for predict (item) sales volume according to date and store. Firstly, I used default values for Random Forest (Model 1)

Secondly, I applied Grid Search and found best parameters for model. (Model 2) Because of improve model results. Finally, I used princibal components (number of pca=2) with Model 2. Metrics used for evaluation models; MAPE,RMSE, MSE AND MAE. All models are compared and chosen the best.

For detail information, you can check:   https://medium.com/@sezenvural9/store-item-demand-forecasting-ad384d2ee7ec
