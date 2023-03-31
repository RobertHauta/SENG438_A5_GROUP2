**SENG 438- Software Testing, Reliability, and Quality**

**Lab. Report \#5 – Software Reliability Assessment**

| Group \#:   2    |   |
|-----------------|---|
| Student Names:  |   |
| Robert Hauta    |   |
|    Joshua Weir             |   |
|                 |   |

# Introduction

# 

# Assessment Using Reliability Growth Testing 

For the Reliability Growth Testing (RGT) portion in this lab, our group used the Covariate Software Failure and Reliability Assessment Tool (C-SFRAT). The data used in this portion was the provided DATASET1 under the Failure Count datasets.

C-SFRAT provides built-in Model Comparison functionality. The built-in tool uses common statistical goodness-of-fit metrics to compare each model, and find which best demonstrates the input data. THe tool rates each model from 0 to 1, with the best-fit models ranging closer to 1. Shown below are the goodness-of-fit scores for four models: IFR Generalized Salvia & Bollinger, Discrete Weibell (Type III), Negative Binomial (Order 2), and Truncated Logistic.

![Model Comparison](media/modelcomp.jpg)<br>

The Critic(Mean) column shows that the Negative Binomial (Order 2) and Truncated Logistic models are the best-fit.

Regarding the range of the data, we used the Laplace test to select the useful range of data. The Laplace test determines if there is an upward trend in a dataset. When testing the reliabitility of system, this test can be used to validate successive failures in a system. Our data fit an exponential (thus, desirable model) for a 42-point data subset.

Below is a plot of failures/time interval with the predictive model included in the plot.

![Failures](media/failures.jpg)<br>

Below is a failure intensity plot of the dataset.

![Intensity](media/intensity.jpg)<br>

The tools and plots discussed above are crucial in decision-making when given a target failure rate. This information can be leveraged to optimize tracking bugs in pre-release, as well as collecting data to guide the software testing process and maintaining the product after release.

# Assessment Using Reliability Demonstration Chart 

# 

# Comparison of Results

# Discussion on Similarity and Differences of the Two Techniques

# How the team work/effort was divided and managed

# 

# Difficulties encountered, challenges overcome, and lessons learned

# Comments/feedback on the lab itself
