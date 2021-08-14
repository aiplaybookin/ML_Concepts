## Zero-2-One

### CRISP-DM ( Cross Industry Standard Process for Data Mining )
Standard process defined

Consists of Six Phase 

	1.	Business Understanding
	2.	Data Understanding
	3.	Data Preprocessing
	4.	Data Modeling
	5.	Evaluation
	6.	Deployment
	
**Other stratdard process e.g. SEMMA (Sample, Explore, Modify, Model and Assess ).**

### Tasks

	-	Description
	-	Estimation
	-	Prediction
	-	Classification
	-	Clustering
	-	Association

## Data Preprocessing

#### Need for preprocessing?
	-	Obsolete or redundant, constant
	-	Missing values
	-	Outliers
	-	Non compliance data
	-	Cannot be used directly
	
**Examples**

1.	Zip code : 10832, AJNG, 93582, 29437,....

2. Age : 29, -19, D, 34, 54, 300, 30.1, 96, 55, 45,....

3. USA, US, India, Ind, ....

	
#### Handling Missing Values : Different ways to replace missing values

While handling missing data, simply deleting records or fields with missing values may be dangerous in few scenarios.

1.	Replace with constant ( say -999, 0 etc )

2.	Replace with mean

3.	Replace with value generated randomly from the observed distribution of field.

4.	Replace / impute based on other dimensions of record


NOTE : Replacing values is a gamble, depends on domain knowledge and driven by analyst

### Ways to summarize a Variable

#### Measure of Centre

Mean, Median, Mode

#### Meaure of Location

Percentile and quantile

...........this is still not enough!

#### Measure of Spread/ Variability

Range ( min and max )

Standard Deviation = sqrt( sum ( ( x - x_mean )^2 ) / ( n-1) )

*Power of 2 here, makes it sensitive to outliers.*

Mean absolute deviation

Interquartile range

