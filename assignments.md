---
title: Assignments
layout: home
menuItem: Assignments
menuPosition: 6
---

## Assignment 1, Forecasts of the 2020 US Election

This activity will give you practice:
- Developing a research question about prediction
- Picking a measure of predictive performance
- Pre-registering research projects

Tetlock (2005) evaluated the predictions of experts by creating a forecasting tournament that asked questions about the probabilities that the event will take place across many domains. Then, he compared those estimated probabilities to the true outcome of the events. In this activity, your group will create your own forecasting tournament around the 2020 US election, pre-register your design, and then submit your results. Like Tetlock's project, you should have multiple approaches to making predictions and you should have each approach make predictions for several events.

### Schedule

- Form groups: Thursday, September 17, 2020 at 5pm ET
- Pre-registration due: Monday, November 2, 2020 11:59pm ET
- Final results due: Tuesday, November 24, 2020 11am ET (before last class meeting)

### Helpful information


#### Pre-registration

You must pre-register your predictions on the [Open Science Framework](https://osf.io/prereg/) (unless you have permission from us to use a different platform). Before pre-registering, you should read [Nosek et al. (2018)](https://www.pnas.org/content/115/11/2600) to learn more about pre-registration.

#### Project ideas

There is a large literature about forecasting elections. Here are some rough ideas for hypotheses that you might want to pursue:

- Hypotheses about different types of elections (e.g., are people better at predicting House races or Senate races?)
- Hypotheses about how predictions change as the election approaches
- Hypotheses about experts vs simple algorithms vs complex algorithms
- Hypotheses about the accuracy of different approaches to prediction (e.g., individuals vs teams)

Here are some papers that might provide additional ideas:

- Nadeau, R., Dassonneville, R., Lewis-Beck, M., & Mongrain, P. (2019). [Are election results more unpredictable? A forecasting test](https://dx.doi.org/10.1017/psrm.2019.24). _Political Science Research and Methods_.

If you find other papers that are helpful, please share them with us.

## Assignment 2, Replication and extension of [Muchlinksi et al. (2016)](https://doi.org/10.1093/pan/mpv024): Random forest vs logistic regression

Recall that there were several critical comments published in response to this paper. It is quite possible that there remain issues with the paper's claims beyond those that were addressed in the comments and replies. Therefore, you should approach this paper (and all papers) with a healthy dose of skepticism.

1. Replicate the corrected version of [Muchlinksi et al. (2016)](https://doi.org/10.1093/pan/mpv024). Specifically you should make the separation plots (Fig 1), ROC curves (Fig 2), ~~F1-scores (Fig 3)~~, and Table 1 for the main models in the paper. You can find the original replication materials [here](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/KRKWK8) and the updated replication materials [here](http://www.davidmuchlinski.com/political-analysis-replication-files/).

2. Extend their result in some way. Here are some suggestions, but please don’t feel limited to these ideas.
- For which cases does the random forest do better and why? Can we use what this learned from the random forest to build a better logistic regression model? For example, is the random forest discovering interactions between variables or non-linearities or both? For some ideas about how to use random forest and logistic regression together, see [Colaresi and Mahmood (2017)](https://doi.org/10.1177/0022343316682065).
- Find another setting and compare the results from logistic regression and random forest. For some other possible ideas, see [Christodoulou et al. (2019)](https://doi.org/10.1016/j.jclinepi.2019.02.004).
- Reduce or expand the set of predictor variables and see how the results change. Is it fair to compare the [Fearon and Laitin (2003)](https://doi.org/10.1017/S0003055403000534), [Collier and Hoefeller (2004)](https://doi.org/10.1093/oep/gpf064), and [Hengre and Sambanis (2006)](https://doi.org/10.1177/0022002706289303) models which have a small number of predictors to the random forest model, which has a large number of predictors?
- Compare the performance of in-sample and out-of-sampling predictions for the models.
- Train the models on one part of the world and then attempt to use them to predict civil wars in a different part of the world? Which models generalize better?
- Explore alternative approaches to cross-validation, beyond those proposed in [Neunhoeffer and Sternberg (2019)](https://doi.org/10.1017/pan.2018.39). The cross-validation was organized around country-years. Do cross-validation where you leave out years or leave out countries. Do the results change? How do you think cross-validation should be done for this research question? How does the relative performance of the models vary by the year used to separate training and test sets. In footnote 2, [Muchlinksi et al. (2019)](https://doi.org/10.1017/pan.2018.45) argue that 1989 is a particularly unusual year.
- How sensitive are the results to the way that civil wars are measured? For some ideas in this direction see [Sambanis (2004)](
https://doi.org/10.1177/0022002704269355).

### Groups

You should work on this assignment in groups of 2 - 3, and interdisciplinary groups are preferred by not required. If you would like to work in a group of 1 or 4, please email us for permission.

### Schedule

- Send us an email with your group and a sketch of what you are thinking about (you don't have to stick to this sketch so don't worry about it too much): Thursday, October 1 by 11am ET.
- Send us your completed assignment:  Thursday, October 15 by 11am ET.

We recognize that you only have 3 weeks to complete this assignment so please be realistic about what is possible. If the assignment seems interesting and generative you are welcome to keep working on it for the final project.
