If github in unable to render a Jupyter notebook, copy the link of the notebook and enter into the nbviewer:
https://nbviewer.jupyter.org/


# Naive Bayes Classifier: Text Classification - Multinomial, Bernoulli & Gaussian

In this notebook series we will learn how to apply the Naive Bayes algorithms for text classification. We will use a corpora of emails and classify them in one of the two classes: spam and non-spam (ham)

Naive Bayes methods are a set of supervised learning algorithms that use Bayes’ theorem with the “naive” assumption of conditional independence between every pair of features given the value of the class variable.


We investigate three different naive Bayes classifiers. These classifiers differ mainly by the assumptions they make regarding the distribution of the likelihhod of the features $p(x_j \mid y = c)$.

- Categorical features (binary valued) are modeled using the Multivariate Bernoulli distribution 
- Categorical features (multi-valued) are modeled using the Multinomial distribution 
- Real-valued features are modeled using the Gaussian distribution 


In spite of their apparently over-simplified assumptions, Naive Bayes classifiers work quite well in many real-world situations, famously document classification and spam filtering. 

- Two key benefits of Naive Bayes models are.


## Benefit 1: Data Size Requirement
Naive Bayes classifiers **require a small amount of training data** to estimate the necessary parameters. 


## Benefit 2: Naturally Immune to the Curse of Dimensionality
Naive Bayes learners and classifiers can be **extremely fast** compared to more sophisticated methods. The time-efficiency is due to the decoupling of the class conditional feature distributions. It ensures that each distribution can be independently estimated as a one dimensional distribution. This in turn helps to alleviate problems stemming from the **curse of dimensionality**.


## Notebooks
    -- Notebook 1: we use the **Multinomial and Multivariate Bernoulli NB** classifiers.
    -- Notebook 2: we use the **Gaussian NB** classifiers.


