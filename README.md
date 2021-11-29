Below shows my data science projects:                               

# [Project 1: Metacritic Bias Detection (NLP)](https://github.com/jonnb123/MetacriticProject)
* The most controversial game of 2020, The Last of Us: Part II sparked disparity amongst critics and users around the world and this is evident on Metacritic, the review aggregator website. The game scored 94 out of 100 overall from critics – one of the most highly acclaimed games ever. However, the overall user score was 5.6 out of 10 denoting a low-average review score.
* Two deep neural networks were created to detect the level of bias in reviews on the site Metacritic for the top 25 and worst 25 video games of all time. 
* The first model was trained using an Amazon dataset reviewing fine foods on the Kaggle website.
* The second model was trained using data scraped from Metacritic using 22 games.
* An in-depth analysis was carried out using both models on the reviews of three games on Metacritic. One of them being The Last of Us Part II.
* Below shows the accuracy of the superior Amazon model (74% accuracy):

![](/images/accuracyAmazon.png)

* Against the inferior Metacritic model (68% accuracy):

![](/images/accuracyMetacritic.png)

Follow the link for more detail.

# [Project 2: Firm Disciplinary Action (Logistic Regression)](https://github.com/jonnb123/LogisticRegression)
* This project looks at whether a law firm needs disciplinary action from a company based off 11 variables. 
* Outliers were removed from the dataset and multicollinearity was examined using a heatmap:

![](/images/heatMap2.png)

* For logistic regression it is important to remove multicollinearity for the best results.
* Turnover and Family variables were not taken into account in the model because they create multicolinearity and they are not related to what we are trying to predict (disciplinary action).
* Overall the model was 75% accurate with its predictions. 
* Follow the link for more detail.
