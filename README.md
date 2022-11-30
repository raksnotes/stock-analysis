# Stock-Analysis

## Deliverable 1 

### * tickerIndex is set to zero before looping* 

![R1](https://user-images.githubusercontent.com/116187123/204667273-a921c5d0-51b2-48ad-ab09-2a31bec71cbd.png)

### * Arrays are created* 

![R2](https://user-images.githubusercontent.com/116187123/204667916-0d61e1fd-552f-474f-a4db-9f0b228db8c5.png)

### *Loops through all rows* 
*unsure about if statements* For the if statements, I referenced the original script if statements as provided in Module 2 in regard to If/Then
                             

![Screenshot (814)](https://user-images.githubusercontent.com/116187123/204673515-e9404769-cd4c-402f-9e5b-098f8c2b3302.png)


![Screenshot (816)](https://user-images.githubusercontent.com/116187123/204676542-e25f7862-cd2b-4d17-862a-3cf645f75eb7.png)

![Screenshot (819)](https://user-images.githubusercontent.com/116187123/204712400-7e9e2273-7dfa-47d3-9417-8e83316d0462.png)



  
## Deliverable 2 
# Purpose 
### The purpose of this project is to use a method called refactoring to help analyze bigger datasets, and perhaps having the code run more quickly.  

### I used Sub AllStocksAnalysis() done in the Module as a template to complete this challenge. 
### With the Module Work, I was able to output the Values for Ticker, daily Volume and Return for the year 2018. I was able to execute 'AllStocksAnalysis' more than once:
## Results
When I initially ran the Refactored Analysis, I had run into a challenge. The only thing calculated was the run time. 
the execution time for the Refactored Analysis only ran once and showed the below output: 
![VBA_Challenge_2018](https://user-images.githubusercontent.com/116187123/204678025-8e65cda5-f1bd-4574-8781-08fd9cdba7ab.png)
Additional, the output included a blank table with wrong conditional formatting: 
![Screenshot (818)](https://user-images.githubusercontent.com/116187123/204678339-78a73d07-9ce1-4de0-94d2-124b0c7e9ccb.png)


## 2018 with original 
![Stocks 2018](https://user-images.githubusercontent.com/116187123/204651161-2e791002-63ed-480f-99ea-fc974dd1bccc.png)

### Initally the run time for the original script was approximately 33 seconds 
![Screenshot (782)](https://user-images.githubusercontent.com/116187123/204671681-caec70e5-3e42-401b-ba16-7fe0387f49cd.png)
### The run time for the refactored script was approximately 1.25 seconds which is significantly less than the original output




## Summary 
 I would say that a big advantage to refactoring code would be the specifcally the run time. When running my code specifically, I saw that the execution time 
original script in comparison to the refactored script was largely significant. It went from 33 seconds to 1.25 seconds. When I analyzing big data especially real 
world data, I think that a smaller run time would be easier to work with overall. Additionally with conditional formatting, instead of scanning through large data, 
it is visually at ease to see the distinct differences within the data. 
