# ML-Prediciting Customers

![c6829314-6d25-4156-ab6a-5603b2e8af38](https://user-images.githubusercontent.com/124652720/233491668-a2e01420-b032-4c4f-9a33-ac80899d9856.png)

Overview: 

E-Commerece has revolutionazied the way the world shops. Instead of being confined to a two or three stores in town, that open at specific hours and only carry limited stocks, the average consumer can now purchase almost anything, at any time, from anywhere. This great abundance of choice also means that consumers have the ability to be discerning of where they spend their money. My client, Sellio, has contracted me to better understand their customers' buying patterns and i built a pipeline to clean, preprocess, process and transform data, and generated 9 different models, performing 3 grid searches on the best one to create a graph that detects with 89% certainity wether a customer will purchase or not. Given my insights from the data and the usability of this pipeline, I would recommend Sellio: 

Recommendations: 

- Embeds cookies into their pages and when a prospect shows 70% of buying signals, incentvize them with offers
- Expand their product description and convert pages to Sales Funnels to reduce bouncing/exiting by keeping people better engaged
- Market before Holidays and provide special offers during weekdays as well as product launches


Business Problem: 


Sellio is a midsized Ecommerce platform that has been succesfully running for 12 years. Despite this they have seen their market share fall as of recent and want to determine what they could better do to retain and expand their consumer base. So I set out to answer: 

What's our prospective customer's buying process?
How do we maxmize oppruntities for conversion? 
How can we increase repeat customers order and market better to new ones?

The Data Set: 
https://www.kaggle.com/datasets/henrysue/online-shoppers-intention


Methods: 

First we examined the data set for a basic analyazation and determined correlations and what would need to be removed. Then I used a combination of descriptive and statistical methods to determine further relationships. Next, I prepared a pipeline to automate transformations and standardize the resulting dataframe, from there I created 9 models, found the best scores and cross valdiation tests focusing on F1 as the truest measure of the model's effectiveness. Finally I used a combination of my business acumen to substantiate relevant recommendations backed by the data for our stakeholder.

Results: 

In total there were  12,330 different interactions analyzed across 27 variables and our final model had an F1 of 94% and a cross validation score of 90.5%, versus the base model with an F1 of 84% and a cross validate score of 73%. 

F1 Score Comparisions (Dummy vs Decision Tree)
![F1_Score Comparison](https://user-images.githubusercontent.com/124652720/233681335-8f0d1874-a7ae-4c49-beb1-24a9403a2b7c.png)


Dummy Model:
![Dummy_Pipe_graph](https://user-images.githubusercontent.com/124652720/233489261-619ed60b-78a6-4a61-8bd0-e02b7752c8ad.png)

Final Model:
![Forest Pipe Final](https://user-images.githubusercontent.com/124652720/233489379-fbd386c4-ca32-43ee-b83e-98529c41e2d8.png)


Recommendations: 
- Embeds cookies into their pages and when a prospect shows 70% of buying signals, incentvize them with offers
- Expand their product description and convert pages to Sales Funnels to reduce bouncing/exiting by keeping people better engaged
- Market before Holidays and provide special offers during weekdays as well as product launches

Going Foward: 

Expanding the pipeline and using to give real time updates to the customers and company would our be our recommendation, as well looking for differences in categories.
