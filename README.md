# World Happiness Report Data Analysis

## Dataset Context
The World Happiness Report is a landmark survey of the state of global happiness. The first report was published in 2012, the second in 2013, the third in 2015, and the fourth in the 2016 Update. The World Happiness 2017, which ranks 155 countries by their happiness levels, was released at the United Nations at an event celebrating International Day of Happiness on March 20th. The report continues to gain global recognition as governments, organizations and civil society increasingly use happiness indicators to inform their policy-making decisions. Leading experts across fields – economics, psychology, survey analysis, national statistics, health, public policy and more – describe how measurements of well-being can be used effectively to assess the progress of nations. The reports review the state of happiness in the world today and show how the new science of happiness explains personal and national variations in happiness.

### Dependencies
This project requires Python 3 or above  and the following Python libraries installed:
  - [Numpy](http://www.numpy.org/)
  - [Pandas](https://pandas.pydata.org/)
  - [Matplotlib](https://matplotlib.org/)
  - [Seaborn](http://seaborn.pydata.org/)
  - [Scikit Learn](http://scikit-learn.org/)
  
### Features
  - GDP per capita
  - Social support
  - Healthy life expectancy
  - Freedom to make life choices
  - Generosity
  - Perceptions of corruption
  
### Target
  - Happiness Score
  
### Predictive Modelling
  - Linear Regression (univariate)
  - Linear Regression (multivariate)
  - Polynomial Regession 
  
### Models trained on
| Algorithm                    | RMSE          |
| -------------------------    |:-------------:|
|Linear Regression(univariate) | 0.42          |
|Linear Regression(multivriate)| 0.09          |
|Linear Regression(multivriate)| 0.08          |
|Polynomial Regression         | 0.09          |


### Conclusion
  - Happiness score does not only depend on GDP per capita
  - Happiness score depends on GDP(money) and also on Health
  - Regression Model works quite good in our happiness Dataset.
  - World happiness doesn't define generosity, generosity has no remarkable impact on Happiness score.
