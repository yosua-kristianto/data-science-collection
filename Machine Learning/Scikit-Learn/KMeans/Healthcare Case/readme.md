# Healthcare Dataset

Well, recently I stumbled myself on having interest in healthcare industry. This dataset believed to be augmented to mimic the healthcare dataset, which probably not really, but let's give shout out to the author (prasad22)[https://www.kaggle.com/datasets/prasad22/healthcare-dataset].

In this notebook, I want to use KMeans. For what? Let's see insight correlation of medical condition with its medication. This may answer some odd question like why giving Cancer medical condition a Paracetamol?

*Breaking my habit on using semicolon ; when using Python

I performing two different experimentation to the data.

First, is to augment the categorical data, into One hot-encoded data. For example I got Gender column. Before, the data will be 'Male', or 'Female'. Now, if the data is 'Male', it will shown as two distinctives columns is_male = 1 and is_female = 0. Which making the feature too complex, clocking at 17.

Second, is to augment the categorical data, into numerical expression. For example, the Gender column. Male will be 1 and Female will be 2. Which the feature is not really complex. However, the model must be able to deal with non-binary value, which more complex in value-wise. 

When I check both coorelation data, both approaches had similar coorelation results, clocking at near zero value, which increase my worry about this experimentation, about whether I should continue using this data or not. Because zero coorelation mean, as you know, can messing up the cluster and even any predictive analysis.

Well, it's augmented anyway, so ya. Moving on.