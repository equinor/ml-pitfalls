# Notebooks

The main notebook is [`A_simple_classification.ipynb`](./A_simple_classification.ipynb).

The other notebooks do various experiments, such as:

- Balancing classes with SMOTE: what to watch out for.
- The curse of dimensionality: high dimensional spaces are weird.
- Dealing with categorical features: how should you encode them?
- The effect of bad labels: how many incorrect labels will ruin your model?
- Encoding time features: one hot, cycles, or something else?
- Reproducing Haklidir and Haklidir (a poor machine learning paper).
- Should you scale the target in a regression problem?
- Splitting autocorrelated data: a major cause of leakage.
- Splitting imbalanced data: usually a problem for minority classes.


## TODO

- Should you _always_ apply regularization in regression problems? E.g. see [this](https://stats.stackexchange.com/questions/443092/in-regression-why-not-use-regularization-by-default) and [this](https://stats.stackexchange.com/questions/403459/should-mle-estimation-always-be-using-penalizers).
- Related: how can you interpret the coefficients of a regularized model? Or is it not a safe thing to do? (To put it another way, are the OLS coefficients somehow more truthful than Ridge?)
- Imputing missing data: what difference does it make? (Drop rows vs replace with mean vs regression.)
- Scaling before splitting: another source of leakage. (Or, for example, doing CV on already-scaled data.)
- Standardize or normalize?
- Polynomial expansion before or after standardization? [See this notebook.](https://gist.github.com/kwinkunks/0243eef4bae18b24b9d46ebbdd7fc4f9#file-feature_transformation_order_for_regression-ipynb)
- Which cost function, and should cost function match the evaluation metric?
- Scaling dummy-encoded data (a bad idea).


## Licenses

These notebooks are offered under two licenses:

- **Creative Common Attribution (CC BY)** for the text.
- **MIT** for the code elements.

(The repo as a whole is CC BY.)
