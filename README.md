# Predictive-Telemarketing
Built decision tree classifier using Python (scikit-learn) to impove bank telemarketing by predicting whether or not a client will subscribe to a term deposit following a telemarketing call (binary classification). Resulted in 84% recall, meaning that this model accurately predicted 85% of total relevant results.

Used Jupyter Notebooks to demo this project to Analytics Team at Urban Outfitters, Inc, highlighting the results and how they can be useful to an actual bank.

## Prerequisites
Jupyter Notebook

Python libraries:
- sklearn
- pandas
- numpy
- matplotlib
- seaborn
- pydotplus

Data source:
- UCI Machine Learning Reporitory ( https://archive.ics.uci.edu/ml/datasets/bank+marketing )

## Results & Takeaway
Acuracy
- This model accurately classified 84% of marketing calls as being successful or unsuccessful

Recall
- This model accurately classified 85% of successful marketing calls 
- This is the most important statistic for Banks as they are more interested in predicting successful engagements rather than unsuccessful ones.

Important Features
- The most important factors that played a role in predicting if a call will be successful not were the job type of the client, outcome of the previous call, and the number of days since the client was last contacted.
