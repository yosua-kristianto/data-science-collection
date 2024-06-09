# ML Team Assignment: Credit Default Classifier

Credit crisis is a condition in the financial system caused by disruptions in the normal process of cash flow that supports the economy [^1]. For example, the operational activities of a farmer begin by obtaining a credit loan from a bank to purchase seeds for planting. One day, a disaster occurs, leading to the farmer's crop failure. Consequently, the farmer fails to repay the credit loan. However, at the same time, the bank also requires the turnover of that money to carry out its operations.

The chosen case is extracted from the journal titled 'The comparisons of data mining techniques for the predictive accuracy of probability of default of credit card clients' [^2]. In the third quarter of 2006, Taiwan experienced a credit crisis. This occurred because Taiwanese banks approved credit for borrowers who did not meet the qualifications. The categorization of not meeting qualifications here refers to the ability to repay credit debt.
Considering this, it is necessary to establish a predictive system as a decision-making tool to minimize the risk of granting loans to prospective borrowers who do not meet the qualifications. This journal also provides the dataset to be used for training purposes [^3].

This project contains another implementation of the predictive default credit classifier, in which was already implemented by Yeh & Lien in 2009 using various data mining techniques. 

## Installation

> The main environment are using Conda. To create new conda environment, install Anaconda, and then run the following command:
>
> `conda env create ml_team_assignment_credit_default_classifier`
>
> To activate the conda environment, run the following command:
> 
> `conda activate ml_team_assignment_credit_default_classifier`
>
> To install package dependencies, run the following command:
>
> `conda install lightgbm matplotlib scikit-learn pandas`
>
> This command line will install [LightGbm](https://lightgbm.readthedocs.io/en/latest/index.html), in which is the main machine learning algorithm that used in this project. Alongside lightgbm, it is installing matplotlib for visualization, scikit-learn for model evaluation, and pandas for data pre-processing. 


## References
[^1]: [KENTON, W. (2023, October 30). Credit Crisis: Meaning, Overview, Historical Example. Retrieved from Invenstopedia: https://www.investopedia.com/terms/c/credit-crisis.asp] (https://www.investopedia.com/terms/c/credit-crisis.asp)
[^2]: Yeh, I.-C., & Lien, C.-h. (2009,). The comparisons of data mining techniques for the predictive accuracy of probability of default of credit card clients. Expert Systems with Applications, 2473-2480.
[^3]: [default of credit card clients dataset](https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients)