# SpectraTel Customer Churn

In this project, I investigated customer churn in a telecommunications company using SQLlite server and a Tableau dashboard.

SpectraTel is a mid-level telecommunications company dealing with high levels of customer churn that are hurting its revenue upside. 
Analyzing customer information data as well as product trends have provided several key insights into the problems facing Vodafone as well as
possible solutions.

Jump straight to the Tableau dashboard <a href="https://public.tableau.com/app/profile/spencer.fong/viz/CustomerChurnDashboard_17709383823040/Dashboard1?publish=yes&showOnboarding=true" target="_blank">here</a>

For my SQL code, click [here](google.com)

# Data Explanation

SpectraTel's customer data consisted of one table with the following columns:

<img src="/assets/data_structure.png" width="250">

The most important variables in this analysis were tenure (length of time contracted to SpectraTel), contract type (Month-to-Month, One-year, and Two-year), and churn rate.

# Executive Summary

SpectraTel runs a ~33% churn rate on average. This is an acceptable churn rate that allows them to hit necessary profit margins and inrease revenue thanks to customer growth. However, SpectraTel found that revenue was lower than expected in the most recent quarter and an analysis was completed to pinpoint areas of weakness and growth.

The first insight that was discovered was the weakness in Month-to-Month contracts as compared to other contract types.

<img src="/assets/Contract-type.png" width="450">

As shown, Month-to-Month contracts suffer from significantly higher churn rates than other types. ~46% vs ~ 16%. Indeed, One-year and Two-year contracts have extremely low churn rates, meaning that any reduction to Month-to-Month churn rates will have an even greater effect on overall company churn rate.

The second insight that was discovered is the extremely high churn rates of contracts within their first year.

<img src="/assets/tenure-churn.png" width="800">

This insight is especially important because it affects not only Month-to-Month contracts, but One-year and Two-year contracts as well. This implies that contracts within their first year are inherently unstable, a possible point of address for SpectraTel.

What is the actual impact of these increases in churn rate though? Using SpectraTel's average 33% churn rate as a baseline, a estimate of total customer and revenue losses was created in order to measure the true impact of customer churn.

The first chart shows the estimated difference in customers lost during the first year versus other years.

<img src="/assets/Customers-churned.png" width="800">

As shown, nearly 500 customers are lost over the average during the first year. This is a very high rate that needs to be addressed.

The second chart shows the estimated revenue loss over the first year, separated by contract type.

<img src="/assets/Revenue-loss.png" width="250">

This chart quantifies even further the cost of sustaining such a high churn rate in the first year. Revenue losses when added up exceed $3.5 million from lost customers.

Ulimately, the analysis comes away with two suggestions: 

First, address first year contracts. With $3.5 million in losses from customer churn, SpectraTel can afford to lower prices or offer deals to first year customers. Even at lower prices, if customers stay on past the first year we see that they tend to become long-lasting paying customers.

Second, address Month-to-Month contracts. Incentives to move to One-year and Two-year contracts may be a solution. However, this should be approached carefully and with further analysis because the revenue impact is less clear than first year contracts.

This concludes the customer churn analysis.

