# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
<img width="716" alt="Screen Shot 2021-11-28 at 8 25 56 PM" src="https://user-images.githubusercontent.com/88211298/143808832-2d9d4edf-80fd-4fcb-8258-0c5edbd8a30f.png">

1.We observed from Pr(>|t|), we can see vehicle_length and ground_clearance have very low probability that are lower than 0.05. That means they are non-random amount of variance to the mpg values in the dataset.<br/>
2.No, the slope of the linear model is not to be zero due to vehicle_length and ground_clearance are dependent valuable that can be explained by the model.<br/>
3.The linear model predicts effectively but not perfect effectively because we have adjusted R-squared 0.6825
## Summary Statistics on Suspension Coils
<img width="524" alt="Screen Shot 2021-11-28 at 8 51 27 PM" src="https://user-images.githubusercontent.com/88211298/143810816-940f0cd5-613b-44e3-8e8a-58449537cc33.png">
<img width="378" alt="Screen Shot 2021-11-28 at 8 51 39 PM" src="https://user-images.githubusercontent.com/88211298/143810830-7ddb30bb-8c5f-40ad-b8df-0c125130b4d8.png">
If we analyze from total_summary, it's not exceed 100, but lot3 has a variance greater than 100 because some extreme data inside lot3.
## T-Tests on Suspension Coils
<img width="473" alt="Screen Shot 2021-11-28 at 9 45 56 PM" src="https://user-images.githubusercontent.com/88211298/143815155-6f7cbf96-3610-4069-a28a-32cc64d18305.png">
The total PSI has p-value greater than 0.05, which means we should not reject the null, it's random.
<img width="431" alt="Screen Shot 2021-11-28 at 9 47 25 PM" src="https://user-images.githubusercontent.com/88211298/143815270-19f6ff47-6de2-4f61-a755-264aed47ff5c.png">
<img width="511" alt="Screen Shot 2021-11-28 at 9 47 47 PM" src="https://user-images.githubusercontent.com/88211298/143815299-03c53ac9-9f36-4990-86cb-326cdaca84da.png">
The same results above, both of them have p-value greater than 0.05, we can't reject the null hypothesis.
<img width="511" alt="Screen Shot 2021-11-28 at 9 49 48 PM" src="https://user-images.githubusercontent.com/88211298/143815467-31c41fa1-661f-4cf6-afd6-472642575c0e.png">
The p-value is smaller than 0.05, we reject the null hypothesis, it's not random.
## Study Design: MechaCar vs Competition
I am trying to test highway fuel efficiency because fuel efficiency would be of interest to the consumers.<br/>
The null hypothesis: There is no difference between MechaCar and competitors.<br/>
The alternative hypothesis: There is difference between MechaCar and competitors.<br/>
I'd like to use two-sample t-test because it compares two companies if they have different fuel efficiency by random select data from those.<br/>
I need mpg for MechaCar and Competitors, and test for the mean value to compare overall performance in companies.
