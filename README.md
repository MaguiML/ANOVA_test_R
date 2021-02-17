# ANOVA test in R


We are going to explore ANOVA to test a hypothesis concerning more than two groups. ANOVA  tell us if one group mean is distinct of others but it doesn't know which. We are going to run a ‘post-hoc analysis’.

## 0. The problem

We are going to use  the *diamonds* dataset from *ggplot2* package.

 Our hypothesis are:

*    **Null Hypothesis**:  the mean of carat weight of the diamond is equal across all the quality cuts (Fair, Good, Very Good, Premium, Ideal)
*    **Alternative hypothesis**: The mean carat is distinct in cuts.

## 1. Import and exploring dataset

Here we are import the dataset and  see the three first rows:
