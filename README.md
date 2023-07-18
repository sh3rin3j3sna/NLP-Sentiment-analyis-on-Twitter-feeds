# NLP-Sentiment-analyis-on-Twitter-feeds
The project aims to analyse sentiments attached to the COVID updates in public using Twitter data. 

### Introduction
The New York Times reports that "Twitter is now the place where public officials make statements, activists pressure politicians, and reporters announce their latest scoops." Twitter has an estimated 330,000 users in New Zealand, with the majority of users being young adults aged 18 to 29, implying that there is one Twitter user for every 15 New Zealanders. It's interesting to see what issues are now trending and what sentiments New Zealanders have expressed on Twitter. Especially during the COVID-19.(the data set is by webscrapping)

The purpose of this study is to discover and comprehend the important themes in New Zealand's Covid-19-related Twitter feed. The project employ natural language processing (NLP) as a technique to investigate Twitter feeds in order to achieve this goal efficiently. First, we clean the Twitter feeds by removing punctuation, stop words, and words with lengths less than three. Then we use tokenization, stemming, and lemmatization to determine the root word for each word. 

For example, we group stay, stay, stays, and stayed together under the root word stay. Most crucially, we use the Latent Dirichlet Allocation (LDA) model to model topics. This allows us to identify subjects that appear frequently in Covid-19-related tweets. Furthermore, we use sentiment analysis to gain a better grasp of the emotional reactions to tweet feeds. 
