# linear-regression-sklearn
2D and 3D multivariate regressing with sklearn applied to cimate change data  
Winner of Siraj Ravel's [coding challange](https://youtu.be/vOppzHpvTiQ?t=7m31s)

## Overview
The notebook is split into two sections: 
* 2D linear regression on a sample dataset [X, Y]
* 3D multivariate linear regression on a climate change dataset [Year, CO2 emissions, Global temperature].

Because of the small amount of data, and the random 10% of data chosen for testing, the scores have high variance.  

2D Linear Regression | 3D Multivariate Linear Regression 
:---: | :---: 
R<sup>2</sup> (Score):  0.651237006724 | R<sup>2</sup> (Score): 0.968933216107
![](https://github.com/ludobouan/linear-regression-sklearn/blob/master/data/2D_data.png) | ![](https://github.com/ludobouan/linear-regression-sklearn/blob/master/data/3D_data.png) 
![](https://github.com/ludobouan/linear-regression-sklearn/blob/master/data/2D_regression.png) | ![](https://github.com/ludobouan/linear-regression-sklearn/blob/master/data/3D_regression.png) 


## Usage
Run the jupyter notebook `linear_regression.ipynb`

##Challenge
> The challenge for this video is to use scikit-learn to create a line of best fit for the included 'challenge_dataset'. Then, make a prediction for an existing data point and see how close it matches up to the actual value. Print out the error you get. 

> Bonus points if you perform linear regression on a dataset with 3 different variables

## Dependencies
* matplotlib
* pandas
* numpy
* seaborn
