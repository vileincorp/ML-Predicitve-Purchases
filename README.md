# ML-Prediciting Customers

![c6829314-6d25-4156-ab6a-5603b2e8af38](https://user-images.githubusercontent.com/124652720/233491668-a2e01420-b032-4c4f-9a33-ac80899d9856.png)


Overview:

E-commerce has revolutionized the way the world shops. Instead of being confined to a limited number of stores with specific operating hours and limited stocks, consumers now have the ability to purchase almost anything, at any time, from anywhere. With this abundance of choice, consumers have become more discerning about where they spend their money. My client, Sellio, has contracted me to gain a better understanding of their customers' buying patterns. I have built a pipeline to clean, preprocess, process, and transform the data. I have also generated nine different models, performed three grid searches on the best model, and created a graph that can detect with 89% certainty whether a customer will make a purchase. Based on the insights from the data and the usability of this pipeline, I would recommend the following to Sellio:

Recommendations:

Embed cookies into their pages and incentivize prospects with offers when they show 70% buying signals.
Expand product descriptions and convert pages to sales funnels to reduce bouncing and keep customers engaged.
Market before holidays and provide special offers during weekdays and product launches.
Business Problem:

Sellio is a mid-sized e-commerce platform that has experienced a recent decline in market share. They want to determine how they can better retain and expand their consumer base. To address this, I set out to answer the following questions:

What is the prospective customer's buying process?
How can we maximize opportunities for conversion?
How can we increase repeat orders from existing customers and improve marketing to attract new ones?
The Dataset: https://www.kaggle.com/datasets/henrysue/online-shoppers-intention

Methods:

First, we examined the dataset for basic analysis and determined correlations and variables that needed to be removed. Then, I used a combination of descriptive and statistical methods to explore further relationships. Next, I prepared a pipeline to automate transformations and standardize the resulting dataframe. From there, I created nine models, evaluated their scores, and performed cross-validation tests, with a focus on using F1 as the true measure of the model's effectiveness. Finally, I used a combination of business acumen and data-backed insights to provide relevant recommendations to our stakeholders.

Results:

The dataset consisted of 12,330 different interactions analyzed across 27 variables. The final model achieved an F1 score of 94% and a cross-validation score of 90.5%, compared to the base model with an F1 score of 84% and a cross-validation score of 73%.


Regenerate response

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
