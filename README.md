## New York Times Comments Data

### 1. Idea
What are people reading? What is their sentiment towards it? What topics are popular? Finally, would it be possible to model individuals' preferences knowing the topics they're interested in and their sentiment towards them?
<br>
- In an attempt to answer the above questions the New York Times articles are web scraped using links available in the kaggle New York Times Comments Data data set (step 1 notebook). <br> 
- A Latent Dirichlet Allocation model is applied to learn the associated topic distribution (step 2 notebook). <br>
- Each article is assigned a primary and secondary topic, article specific as well as topic specific sentiment is evaluated based on the comments data (step 3 notebook). <br> 
- A simple predictor is built to validate the topic assignment (step 4 notebook). Finally some open ended analysis is carried out on the resulting data set of topic tagged and sentiment evaluated articles.
<br>

### 2. Data
New York Times Comments data set available on kaggle (https://www.kaggle.com/aashita/nyt-comments).
<br>
### 3. Method
 - Step 1 - data acquisition <br>
 Nothing facy here, using urls from the data set full texts of articles are downloaded to be used as training data in topic modelling.
 - Step 2 - LDA modelling 
 - Step 3 - comments sentiment analysis
 - Step 4 - validation
 - Step 5 - exploratory analysis

