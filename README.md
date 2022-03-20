### ukraine-conflict-twitter-sentiment-analysis-Recommandation-System

Data: Datasets contain tweets monitoring the current ongoing Ukraine-Russia conflict. 
data source:[Ukraine Conflict Twitter Dataset (10.8M tweets)](https://www.kaggle.com/datasets/bwandowando/ukraine-russian-crisis-twitter-dataset-1-2-m-rows/code)

**What did I do?**
1. Near 1 million tweets were posted between 17 Mar and 18 Mar about Ukraine Conflict, I converted them into Feather File Format for fast processing purpose, and less ram usage.
2. I used certain text mining techniques, including tokenization, sentiment analysis, keyword visualization (wordcloud maps), and ordinary exploartion (location, time distributions)
3. I also built a recommendation system for recommending 10 most sentimentally alike tweets based on their cosine similarity
4. I applied most popular classifier methods (including SVM, random forest, decision tree, naive bayes, gradient boost and xgboost) to build predictive models that predict the sentiment of the tweets, and SVM model provides the best accuracy (99%)
