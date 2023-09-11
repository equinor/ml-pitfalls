# ml-pitfalls

Notes and notebooks about **Pitfalls in machine learning**, including why they happen, how to recognize them, and how to avoid them.

**Pitfalls** is probably not the best thing to call them, because it makes it sound as if they are scattered about, few and far between, and you'd have to be a bit unlucky to fall into one. But this is not the case.

It also makes it sound as if you'll know when you fall into one. Everything will go dark and you'll twist your ankle or fall on your backside when you land. But this is not true either.

The reality is that machine learning pitfalls are everywhere, and quite large. And you will almost certainly fall into them on a regular basis. For sure you have already fallen into them, probably several times. And unfortunately, you won't usually  be able to tell if you're in one or not &mdash; even though everything is completely broken and possibly even on fire.

Basically, I need a better metaphor...


## The big ones

This is important, so let's start with the punchline. They say 'untested code is broken code' and the same applies to machine learning projects:

> Unverified pipelines are broken pipelines.

If you have not thoroughly and critically reviewed and documented your machine learning pipeline, with the eyeballs and experience of others, then your pipeline is probably hiding one or more of the following pathologies:

- Poor project design
- Poor data
- Leakage
- Modeling mistakes (especially underfitting, overfitting)
- Improper evaluation
- Improper application
- Improper deployment
- Insufficient engineering
- Insufficient governance

All of these pathologies can lead to unreliable, unsafe, and unethical models.

Your project is not suffering from these problems because you are a bad practitioner of machine learning, but because machine learning is hard and impossible to get perfectly right every time.

The reality is that making scientific and engineering recommendations on the basis of machine learning models is new to most of us, in the same way that scientific experimentation was new to most practitioners in the 17th century. While we learn how to get good at it, we need to help each other stay out of these pitfalls.


## Approximate plan

| When | What                                |
|------|-------------------------------------|
| 1000 | Welcome and introduction            |
|      | A series of unfortunate events      |
|      | Breakpoint                          |
|      | David Wade: Hard lessons            |
|      | Finish the examples                 |
| 1300 | Lunch                               |
| 1345 | Case studies                        |
|      | Breakpoint                          |
|      | Tooling for _Safety by design_      |
|      | Hackathon: Building smoke detectors |  


## The notebooks

- [A simple classification](notebooks/A_simple_classification.ipynb)

More examples and playgrounds:

- [Balance_classes_with_SMOTE.ipynb](notebooks/Balance_classes_with_SMOTE.ipynb)
- [Curse_of_dimensionality.ipynb](notebooks/Curse_of_dimensionality.ipynb)
- [Dealing_with_categorical_features.ipynb](notebooks/Dealing_with_categorical_features.ipynb)
- [Effect_of_bad_labels.ipynb](notebooks/Effect_of_bad_labels.ipynb)
- [Encoding_time_features.ipynb](notebooks/Encoding_time_features.ipynb)
- [Scaling_the_target.ipynb](notebooks/Scaling_the_target.ipynb)
- [Splitting_autocorrelated_data.ipynb](notebooks/Splitting_autocorrelated_data.ipynb)
- [Splitting_imbalanced_data.ipynb](notebooks/Splitting_imbalanced_data.ipynb)

And one reproduction of a paper:

- [Reproducing_Haklidir_and_Haklidir](notebooks/Reproducing_Haklidir_and_Haklidir.ipynb)
