**University of Michigan Stats with Python Notes**



**Course 1 - Week 4**



**Sampling Distributions**

Size of samples - effects variation in estimates

\# of samples - effects the normality of distribution

Because we know that many samples result in a normal sampling distribution, we can use the size of the sample to estimate variation parameters in a hypothetical sampling distribution.

One sample -> estimates of sampling distribution -> estimates of population



**Population Inference - Single Probability Sample**

1. Compute point estimate

​	- unbiased aka representative

​	- if unequal probabilities of selection, use weighs when computing point estimate

2. Estimate sampling distribution variance of point estimate

​	- Standard Error = 2x STD of Point Estimate (95% confidence)

3. Form a confidence interval

​	- Point estimate +- Standard Error

4. Test Hypothesis

​	- Test stat = (pred - null value) / standard error

​	- p-value probability of getting this test statistic based on a sampling distribution of test statistics



**Population Inference - Non-Probability Sample**

\- Can’t use sampling theory



*Methods:*

1. Quasi-Randomization

​	- Combine Probability Sample & Non-probability sample data

​	- Build model to predict which source data came from (Binary Classification)

​	- Survey Weight = 1 / Predicted Prob

​	- Variation of sampling distribution estimated by sampling sample data

2. Population Modeling

​	- Predictive modeling to predict aggregate sample values on variables using auxiliary data on people in target population

​	- Compute estimates of interest using estimate totals

​	- weighted mean = predictive total estimate / estimated population size



**Complex Samples**

\- Stratification

\- Clustering

\- Weighting Sample’s to represent population so sample is not biased

\- Non-response weights

![Screen Shot 2021-04-25 at 5.30.30 PM](/Users/miesner.jacob/Desktop/Screen Shot 2021-04-25 at 5.30.30 PM.png)