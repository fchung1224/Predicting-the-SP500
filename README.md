# final-capstone-report

## Instructions

To complete this report, open the template Rmd file and write your report. Make sure to hide all code but include that necessary code in the Rmd to create the visualizations and the tables that you need. When done, knit the file to pdf or html format. Provide any comments/questions about this report in the section below 

**Learning Goals:** This is an opportunity synthesize all that you've learned about correlated and demonstrate your understanding by writing a concise, but thorough report on your analysis. You should go beyond what you did in the initial report, considering other research questions, refine the original work, and take feedback into account. 

**Comments/Questions to Prof. H:** 



*Next section to be completed by Prof. H and preceptors. Do not type below this line.*

## Feedback 

Heggeseth Feedback:

- Similar intro but expanded to include VAR
- Intro could have used a bit explanation for terminology for readers who are not familiar with finance. 
- Kalman filter needs more explanation as well as a citation. What does it mean for the data to fill in the values... is it the same value as the day before? is it similar? give the reader some sense of what value goes in there and how does that impact your analysis... Is this technique used in other papers that analyze the stock market? Because I'm more concerned if it keeps the existing correlation structure that is observed without drastically impacting the conclusions... The two plots of open and closed do not do enough to alleviate my concerns.
- the methods section could have included a bit more information about how ACF and PACF get used to select the best model for the errors.
- In the methods, epsilon is suddenly introduced without any other notation to ground or define what that means..
- You need to define notation and use it if it is more effective for communication.
- The null hypothesis for ljung-box is independence, not correlation, so you actually want large p-values for the residuals..
- You switch from plots of the adjusted close to returns.. This jargon needs to get explained.
- Choose graphs to include that give more information that you could express in 1-2 sentences. Many of these graphics (many acf plots) could have been excluded from the report.
- Generally, good discusion on VAR
- What do you mean by "some of the variables are highly persistent"?
- 

Grade: 93/100

Overall Feedback:

