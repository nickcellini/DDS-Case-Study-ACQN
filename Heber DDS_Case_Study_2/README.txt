
22 July 2018

Project 2 Notes:

Data files:

	- Study2 - Full data set, all 35 variables. No missing values.
	- Study2n - Data set with only the numerical variables from Study2.
	- Study2n22 - Data set derived from Study2n. The variables "EmployeeCount", "StandardHours",  "JobInvolvement", and 			"PerformanceRating" were left out from Study2n to create this new data set.

The reason that Study2n was created is that both Principal Component Analysis and Factor Analysis can only be done on numerical variables. Some of our variables (like Married and Gender) can be recoded as numerics. I have not done that yet. Study 2n22 was created because two variables (EmployeeCount and StandardHours) are the same for everyone so they do not have any varience. Two more variables (JobInvolvement and PerformanceRating) have identical 1st quartile and 3rd quartile values. Principal Components Analysis (at least the procedure I used) requires that there be variability and that there be a difference between 1st and 3rd quartile values so the analysis can look at variability.

Figures:
	
	- I put in histograms (box plots) of each variable. None of these are "prettified" but that will be easy to do if we want to use these for final data.
	- I made scatterplots of a few variables agains MonthlyIncome. I didn't learn a lot, but this was just exploration and I decided to move on without doing more. The scatterplots are included but again are not "prettified".
	- Both Principal Component Analysis and Factor Analysis results can be represented in Scree plots, which I created. Scree plots are one important method of deciding how many components to keep in the final model. I included Scree plots for the Principal Component Analysis and the Factor Analysis, I also did Factor Analysis for different numbers of factors (2, 3, 4, and 5). I put in plots for these. These plots are also used to determine which factors to include in the analysis, and graph out which variables contribute to which factors.


Other:
	- Overall, both PCA and FA indicated that 3 factors or components worked best as a model (a model built without considering any of the non-numerical variables). Besides the plots there are tables which are important for supporting and documenting the reasons for this conclusion. For now I have not put those in. I can create a markdown document of that if and when people want to see that.