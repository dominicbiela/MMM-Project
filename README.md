# MMM-Project
Marketing Mix Model for MSc Applied Data Science

**Introduction**

A Marketing Mix Model strategy was compiled to walk through the stages required to apply to a dataset.
Understanding the impact of marketing helps identify successful campaigns, but more importantly predicts future success.
Marketing Mix Modelling (MMM) is a statistical analysis that estimates marketing influence.
By clarifying clear steps on building and deploying a MMM, it provides opportunity for product development and market positioning. 

An OLS model is used due to its ease of interpretability. Whilst also being quick and easy to apply, which is an important factor in a fast-paced client environment.
A Marketing channel may sometimes amplify other channels, resulting in and exponential impact. Therefore, Logarithmic models can be utilising to identify this behaviour.
ย 
 
 **Adstock**

![image](https://user-images.githubusercontent.com/25266458/129876411-386d3288-f90f-4b74-a6bc-066989feb4a6.png)


Adstock is the theory on continued marketing effect, beyond the point of advertising. Therefore, data is transformed using a Simple Decay-Effect Model:
ย 


๐_๐ก=๐ฅ_๐ก+๐๐_(๐กโ1)           ๐ก=1,โฆ, ๐

**Diminishing Returns**

![image](https://user-images.githubusercontent.com/25266458/129876150-bf988aeb-b3f6-439d-86ae-5037731021f6.png)

Diminishing Returns is the diminishing impact of spending more, as the advert has reached the target audience and saturated. Transformed using a Negative Exponential curve:



๐ฆ_๐ก=(1โ๐^(โ๐ฅ_๐ก/๐ผ) )โ๐ฝ  



**Contents**
- Data Exploration
  - Identifying Variables
  - Plotting the Data
  - Correlation
  - Variance Inflation Factor

- Modelling
  - Functions
  - Train Test Split Test
  - OLS Model
  - Log-Lin
  - Log-Log
  - Adstock
  - Diminishing Returns
  - Adstock and Diminishing Returns

- Analysis
  - Errors
  - Attribution
  - Return on Ad Spend (ROAS)
