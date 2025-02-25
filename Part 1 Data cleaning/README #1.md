# Section name: Data Cleaning

# Overview: 
This part includes preprocessing of the data done by the team after analyzing the data set provided. 

# Software Used:
Python 

# Types of preprocessing with steps: 
### 1. corrupted/shortened preprocessing : 

After reviewing the data file and data points, it was noticed that more than 30% rows had missing delay values even with the cases of every delay to be null in the whole row. 

Thus, it was crucial to initiate with either shortening the data by dropping the rows or filling the values.

In the whole data, two pattern among the delays were seen:

a>. The sum of arrival delay is the total of all of the other delays which are weather delay, NAS delay, Security delay, LateAircraft delay and carrier delay. 

ArrDelay = weather delay + NAS delay + security delay + LateAircraft delay + carrier delay 


b>. departure delay tend to be the sum of arrival delay and absolute difference of actual and calculated elapsed time.

DepDelay = ArrDelay + | Actual Elapsed time - Calculated Elapsed time |


Therefore, rows with none delay values were completely dropped as there was no methodology to retrieve or impute every missing delay value. Then, remaining missing values of arrival and departure delay were filled using the formulas. 

### 2. Noisy data:

With the help of scatter plot, it was noticed that both Taxi_in and Taxi_out columns had outliers. 

As a solution, Z-score and median imputation were used.

### 3. Format error: 

Two columns with format error were discovered in the whole dataset which were Distance and Dest (destination) respectively representing the values to be zero.

To fix it, for Distance column, values were replaced using similar set of origin and destination.

In addition, a combination of origin and distance were used to replace value zero with accurate classification of Dest column. 


## Files in the folder:
 
|File name...                    |         Description...                   |
|------------------------------- |------------------------------------------|
|Arr_Delay preprocessing - Parul | images + coding file |
|Dep_Delay preprocessing - Abu   | images + coding file |
|Taxi_in prprocessing - Meera    | coding file          |
|Taxi_out_preprocessing - Kamini | coding file          |
|Distance preprocessing - Megha  | coding file          |
|Dest preprocessing - Vidhut     | coding file          |

 
