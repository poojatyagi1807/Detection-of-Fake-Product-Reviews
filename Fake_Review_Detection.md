The focus of this project is to identify features and build a predictive machine learning model to predict fake product reviews on online shopping websites like Amazon. 
Two different approaches are implemented to understand differentiating features that can be used to filter Fake reviews at such websites.

In first approach, predictors like verified purchase, review length, and sentiment polarity of reviews is utilized to predict if a review is fake or not using supervised machine learning models like SVM, Naive Bayes, Decision Tree, Random Forest, Logistic Regression and Latent Drichlet Allocation. By comparing accuracy levels of these models, the most accurate model is choosen.

In second approach, focus is shifted to only review text and using TF-IDF weights supervised predictive models (SVM and Naive Bayes) are trained to predict the class of reviews.


In the jupyter notebook, a complete step by step data analysis can be found as well as the logical reasoning for feature selection and extraction is available.