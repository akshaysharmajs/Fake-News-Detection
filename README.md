# Fake-News-Detection
A machine learning model to detect whether a news article is fake or real using NLP.

-------
Summary
--------
Fake news spreads like a wild fire. People unknowingly share news that they find different without knowing the truth. The agenda behind creating such news can be monetary, political or economic. When someone or something such as a bot try to impersonate someone or some reliable source to spread false information, this can also be considered as fake news.

From our empirical research we have observed and analysed that an automated system sometimes identifies fake news articles better than human do. The automated systems can play an important tool for identifying fake stories, articles, blogs, clicks which manipulate public opinion on social networking sites.
The research in this area is based on two categories of algorithms, text-based, image-based and web scraping based.

Taking into need for the development of such fake news detection system, in this paper we have identified news articles as fake or real by using supervised machine learning classifiers such as Linear Regression (LR), Decision Tree (DT), Random Forest (RF). The feature extraction techniques, Term Frequency–Inverse Document Frequency (TF–IDF), Count-Vectorizer (CV) are used to extract feature vectors from the textual content of articles. The effectiveness of a set of classifiers is observed when they predict the labels of the testing samples after learning the training data using these features extraction techniques. Various supervised ML models are extensively used for categorization of textual data as fake or real.

In order to test a machine learning algorithms, we define two different datasets: training dataset(80%) and testing dataset(20%)
We successfully implemented a machine learning and natural language processing model to detect whether an article was fake or fact. We a total of 73205 articles scraped from our web crawler for which we trained our models. Our models provides accuracy as Logistic Regression (LR) 97.7 %, Decision Tree(DT) 93.64% and Random Forest (RF) 95.2% .When doing such a classification, it is important to check that we limit the number of false positives as they can cause facts to be marked as fake. Text analytics and NLP can be used to work with the very important problem of fake news. We have seen the big impact they can have on people’s opinions, and the way the world thinks or sees a topic.
