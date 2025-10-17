# Data sets found in this folder

## Advertising Data
The TV, Radio, and Newspaper advertising budgets, as well as Sales of a product in 200 different markets. Discussed in Chapter 2 of _An Introduction to Statistical Learning_ by James, Witten, Hastie, Tibshirani, and Taylor. 

Consists of 200 observations on 4 variables.
* `TV`: TV advertising budget, in thousands of dollars
* `Radio`: Radio advertising budget, in thousands of dollars
* `Newspaper`: Newspaper advertising budget, in thousands of dollars
* `Sales`: Thousands of units sold

### Notes 

```python
ads = pd.read_csv('./DataSets/Advertising.csv')
ads.describe()
```

|       |       TV |    Radio |   Newspaper |     Sales |
|:------|---------:|---------:|------------:|----------:|
| count | 200      | 200      |    200      | 200       |
| mean  | 147.042  |  23.264  |     30.554  |  14.0225  |
| std   |  85.8542 |  14.8468 |     21.7786 |   5.21746 |
| min   |   0.7    |   0      |      0.3    |   1.6     |
| 25%   |  74.375  |   9.975  |     12.75   |  10.375   |
| 50%   | 149.75   |  22.9    |     25.75   |  12.9     |
| 75%   | 218.825  |  36.525  |     45.1    |  17.4     |
| max   | 296.4    |  49.6    |    114      |  27       |

## Auto Data
The gas mileage, number of cylinders, weight, and other information for 392 vehicles. This data was taken from the [StatLib library](https://lib.stat.cmu.edu/datasets/) maintained at Carnegie Melon University, and was also used in the book _An Introduction to Statistical Learning_.

Consists of 392 observations on 9 variables.
* `mpg`: miles per gallon
* `cylinders`: Number of cylinders between 4 and 8
* `displacement`: Engine displacement in cubic inches
* `horsepower`: Engine horsepower
* `weight`: Vehicle weight in lbs.
* `acceleration`: Seconds to accelerate from 0 to 60 mph
* `year`: Model year (modulo 100)
* `origin`: Origin of car (1 = American; 2 = European; 3 = Japanese)
* `name`: Vehicle name

### Notes 
The original data set had 397 observations. Of these, 5 were missing values in the `horsepower` column and are removed.

```python
auto = pd.read_csv('./DataSets/Auto.csv')
auto[['mpg','cylinders','displacement','horsepower']].describe()
```

|       |       mpg |   cylinders |   displacement |   horsepower |
|:------|----------:|------------:|---------------:|-------------:|
| count | 392       |   392       |        392     |     392      |
| mean  |  23.4459  |     5.47194 |        194.412 |     104.469  |
| std   |   7.80501 |     1.70578 |        104.644 |      38.4912 |
| min   |   9       |     3       |         68     |      46      |
| 25%   |  17       |     4       |        105     |      75      |
| 50%   |  22.75    |     4       |        151     |      93.5    |
| 75%   |  29       |     8       |        275.75  |     126      |
| max   |  46.6     |     8       |        455     |     230      |

## College Data
Various statistics for colleges and universities in the United States. This data comes from 1995 US News and World Report.

Consists of 777 observations on 19 variables.
* `School`: Name of the college or university
* `Private`: Values 'Yes' or 'No', indicating whether private or public
* `Apps`: Number of applications received
* `Accept`: Number of applications accepted
* `Enroll`: Number of new students enrolled
* `Top10perc`: Percentage of new students from top 10% of high school class
* `Top25perc`: Percentage of new students from top 25% of high school class
* `F_Undergrad`: Number of full-time undergraduates
* `P_Undergrad`: Number of part-time undergraduates
* `Outstate`: Out-of-state tuition
* `Room_Board`: Room and board costs
* `Books`: Estimated book costs
* `Personal`: Estimated personal spending
* `PhD`: Percentage of faculty with PhD's
* `Terminal`: Percentage of faculty with terminal degree
* `S_F_Ratio`: Student/faculty ratio
* `perc_alumni`: Percentage of alumni who donate
* `Expend`: Instructional expenditure per student
* `Grad_Rate`: Graduation rate

### Notes 
This data set was used in the ASA Statistical Graphics Section's 1995 Data Analysis Exposition.

```python
college = pd.read_csv('./DataSets/College.csv')
college[['Apps','Accept', 'Enroll', 'Top10perc']].describe()
```

|       |     Apps |   Accept |   Enroll |   Top10perc |
|:------|---------:|---------:|---------:|------------:|
| count |   777    |   777    |  777     |    777      |
| mean  |  3001.64 |  2018.8  |  779.973 |     27.5586 |
| std   |  3870.2  |  2451.11 |  929.176 |     17.6404 |
| min   |    81    |    72    |   35     |      1      |
| 25%   |   776    |   604    |  242     |     15      |
| 50%   |  1558    |  1110    |  434     |     23      |
| 75%   |  3624    |  2424    |  902     |     35      |
| max   | 48094    | 26330    | 6392     |     96      |

## Kleiber's Law Data
Data containing the body mass (kg) and metabolic rate (kJ/day) of various animals over a wide range of different masses. Data was obtained from folder for exercises from Machine Learning Refined textbook.

Consists of 1498 observations on the two variables: Body Mass (`mass`) in kg, and Metabolic Rate (`meta_rate`) in kJ per day.