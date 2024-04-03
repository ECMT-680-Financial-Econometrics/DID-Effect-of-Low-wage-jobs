# Machine Learning in DID
## [The Effect of Minimum Wages on Low-wage Jobs](https://doi.org/10.1093/qje/qjz014)
Group members: Faye Yang, Lingfeng Shi, Nuha Alamri, Oscar Lu, Qijin Liu, Weizi He.

Introduction:

The study examines the effect of minimum wage increases on low-wage jobs in the U.S. from 1979 to 2016, finding that while the overall number of such jobs remained unchanged following wage hikes, average earnings for low-wage workers increased due to wage spillovers at the bottom of the wage distribution. Despite concerns, there was no significant evidence of job losses, even with higher minimum wages, except for some employment reductions in tradable sectors.

Our group used the **KNN method** in the data pre-processing part, mainly focused on filling in the missing values, and **casual forest** to analyze the heterogeneous effects.

Data:

Methodology: KNN and Casual forest
our group divided the salary distribution based on race, gender, age, and other factors in various US states from 1979 to 2016 by year, then used KNN in machine learning to fill in the missing values, and then defined the feature variables (we chose year and quarter and state number statenum and some demographic characteristics as examples). Additionally, we assume that 'MW_real' is used directly as the treatment variable and 'emp' (employment number) as the outcome variable.

Conclusion:

Colab link: https://drive.google.com/drive/folders/1-qAhrif1STNy8GQkvQ1yuVe3SDfu_dhx?usp=drive_link
