# ml-pitfalls

Notes and notebooks about **Pitfalls in machine learning**, including why they happen, how to recognize them, and how to avoid them.

**Pitfalls** is probably not the best thing to call them, because it makes it sound as if they are scattered about, few and far between, and you'd have to be a bit unlucky to fall into one. But this is not the case.

It also makes it sound as if you'll know when you fall into one. Everything will go dark and you'll twist your ankle or fall on your backside when you land. But this is not true either.

The reality is that machine learning pitfalls are everywhere, and quite large. And you will almost certainly fall into them on a regular basis. For sure you have already fallen into them, probably several times. And unfortunately, you won't usually  be able to tell if you're in one or not &mdash; even though everything is completely broken and possibly even on fire.

Basically, I need a better metaphor...

## The big ones

This is important, so let's start with the punchline:

> Unverified pipelines are broken pipelines.

If you have not thoroughly and critically reviewed and documented your machine learning pipeline, with the eyeballs and input of others, then your pipeline is probably hiding one or more of the following pathologies:

- Leakage of information.
- Overfitting.
- Spurious extrapolation.
- Unreproducible results.
- Unexplainable predictions.

All of these pathologies can lead to unreliable, unsafe, and unethical models.

The reality is that making scientific and engineering recommendations on the basis of machine learning models is new to most of us, in the same way that scientific experimentation was new to most practitioners in the 17th century. While we learn how to get good at it, we need to help each other stay out of these pitfalls.

## Approximate plan

| When | What                                |
|------|-------------------------------------|
| 1000 | Welcome and introduction            |
|      | A series of unfortunate events      |
|      | Breakpoint                          |
|      | David Wade: Hard lessons            |
| 1300 | Apparently lunch                    |
| 1345 | Case studies                        |
|      | Breakpoint                          |
|      | Tooling for _Safety by design_      |
|      | Hackathon: Building smoke detectors |  
