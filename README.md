# Topic Analysis

In the following notebook the first steps to evaluate a Latent Dirichlet allocation model are performed.
In this case latent topics for Tripadvisor reviews are modeled. The coherence measure is used to find the optimal parametrisation of the model.
This model then can be used to find the topics of negative reviews which might have leads to improve the service or lead to reviews
which should be answered by the customer service.
This logic could also be applied to customer complaints to find latent topics in the text and improve customer
satisfaction.

The relevant files are LDA.ipynb and LDA_preprocessing.py. 

The other files are experiments to implement further features at a later point of time.


## Prerequisites

To work with the project the following technologies need to be installed:

- Jupyter Notebook

To run the code successfully in the notebook the following packages need to be installed with the pip install command:

```
nltk
bs4
gensim
spacy
unidecode
contractions
re
pandas
numpy
pyLDAvis
matplotlib
seaborn
```


## Data sources and table structure

The data is from Kaggle and can be found under the following link:

https://www.kaggle.com/andrewmvd/trip-advisor-hotel-reviews


## ToDo

- [x] Prepare data preprocessing
- [x] Fine tune hyperparametrization
- [x] Add topics to reviews
- [ ] Add Cosine Similarity
- [ ] Add Sentiment to each document
- [ ] Set up Graphs for visualisation 
- [ ] Build Flask App



## Authors

* **Simon Unterbusch**