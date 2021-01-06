# Following The Data Science Methodology

Explore the different tasks of a data scientist, and learn how the tasks can help other roles within the data science methodology.

Data science is an enormous field, and it is not only about developing machine learning models or predicting outputs to various scenarios an individual can experience when dealing with data. A data scientist wears different hats and might be responsible for one or more of the following:

* Business understanding
* Data understanding
* Data preparation
* Modeling
* Evaluation
* Deployment

Each of these tasks is linked to each other, and they help other roles within the data science methodology. That's exactly what I focus on in this blog.

You might be asking, what is the data science methodology? It's a methodology that data scientists follow to find a solution to a specific problem, and using the data that is involved.

The data science methodology consists of five iterative steps, and within those steps you have sub-categories that assist data scientists.

## Identifying the problem and the approach to fix the problem

As a starting step, look at what you are trying to solve within a business. The first step to that is understanding the business -- what is the business dealing with, what is their input, what is the final output given by the business, and what are the other factors that lead to the final output. With this information, you get a clear understanding of the business.

As the business audit is done, you also highlight the problem area that the business is facing. Now that you have this information, you move to the next step, which is the analytic approach. In this step, what you typically do is pick an appropriate analytical approach to the problem in question. This usually starts with a descriptive analysis, where you ask questions like "what has gone wrong." Then, you move to diagnostic analysis, also known as statistical analysis, where it is more about "why has this gone wrong." Next, you move to a predictive analysis approach where you look at the consequences if the same trend continues. Here, the question is more about "what going to happen next?" Finally, you come to a prescriptive analytics approach, where you look at how can you solve the problem with "what do I need to do?"

With these two steps, you are done with the first step in the methodology, knowing more about the issue in detail and understanding the business pipeline as well.

## Deduce data requirements and collection methods

Data requirements and data collection are within the second step of the methodology. Here, you define the data that you need to solve the problem that the business is facing. In this step, you must look at the format of data that needs to be collected as well as what particular data should be collected. For example, a data scientist working in a banking sector use case that predicts loan eligibility needs to collect data that includes an individual's monthly income, profession, age, and years in the country to predict if the individual is eligible to get loan.

After aligning your data requirements, the next step is collecting the data and how that data is collected. For example, this could be collecting live streamed data from streaming analytics services, which would give you raw data to work with. The business itself can provide the data set or use web scraping to collect textual data. Most of the data in this step would be raw, and cleaning and understanding the data would be required.
 
## Understand the data and data preparation

After the data has been collected, you begin understanding and preparing the data, which is the third step within the methodology. When it comes to data understanding, the first thing that you ask yourself is "is this data going to answer problem that I am having," and then you start with Exploratory Data Analysis (EDA). In EDA, you generate visualizations and graphs to find relationships between the data that is collected, the relationship that occurs between columns. For example, the salary of a person based on their experience in the industry would be applicable in some companies.

After you understand this data, the next step is preparing the data itself, which takes most of the time within the methodology. Here, you perform a lot of operations on the data such as mitigating the missing data and columns, making the data more readable, substituting and anonymizing the data, and removing the data that is not required. Furthermore, following data manipulation, you also conduct feature engineering, which is conducting operations between columns to come up with new meaningful data that would create new insights within the data. Feature engineering itself is big because you do multiple operations that could include sine, cosine, tans, and additions and comparisons of data within each and every column in the data set.

After the data is prepared and ready to be used, you can continue with modeling and evaluating the model.

## Generate models and evaluate them

Generating and evaluating models is the next step in the methodology. There are two types of modeling, descriptive modeling and predictive modeling. Descriptive modeling tells you what service a particular individual might be interested in and is based on recommendation systems and clustering algorithms. Predictive modeling is where you predict a future value based on key inputs and is based on linear or logistic regression and classification algorithms.

Evaluating the modeling deals with the question of "does the model do what it is intended to do," and you also look into the topic of explaining the model. When evaluating the model, the diagnostic phase is where you see if the model is doing what it is intended to do. If the model is a predictive model, you can use decision trees if the output is aligning to the initial design. If it is a descriptive model, you can use a testing data set that consists of known outcomes, which lets you refine the model accordingly.

Finally, in the evaluation phase, you also work with model explainability, which allows you to explain how the model made this decision; what parameters have been taken into consideration; and what model tuning, accuracy, and error metrics have been considered to make the model give such the prediction.

When you're done generating the models and evaluating them, you move to deploying the model, getting feedback, and refining the model based on the feedback.

## Deploy the model and get feedback

When you have confidence in the the model, you move to the deployment phase where you deploy the model to a limited number people to get feedback on the predictions and to see if the model is good for public use.

After the model is deployed, you receive the feedback from the model's users. The users provide further feedback about the model, and then you can refine the model further, evaluate it, and deploy it again. It goes back to the feedback phase and repeats this process until you have a final model. Then, you can deploy it to a large set of users.

As you can see with this methodology, you can get in-depth insight into your data science pipeline. Additionally, this is an agile methodology, so as you spend more time in each step, you get into a deeper understanding and implementation of the model, and it lets you attain better results in the field of data science.

Original link to blog: https://developer.ibm.com/blogs/following-the-data-science-methodology/
