# Topical Span of Edit Wars in English Wikipedia

This is the code from a  project is run by the [Wikimedia Research Team](https://research.wikimedia.org)  as part of the [Community health initiative](https://meta.wikimedia.org/wiki/Community_health_initiative). Here, we take a language agnostic approach, which focuses on edit wars and attempts to differentiate between topic-centered and person-centered conflicts. For more details about this project, please [visit our page in meta](https://meta.wikimedia.org/wiki/Research:Topical_coverage_of_Edit_Wars).

The main contributions of this work are:

* Implemented a model to measure topical distance between English Wikipedia pages. This model is based on [this work](https://meta.wikimedia.org/wiki/Research:Automatic_new_article_topics_suggestion)
* We found that around ~52% of the users are topic focused (they edit only in one topic), there are ~42% of the contributors that make big jumps across topics. 
* We have found that just 7% of edit wars are cross-topic.
* However, users involved in this cross-topic edit wars are generally very active users, making difficult to assume that those wars are due person-centered conflicts.

In this repository you will find the following notebooks:

* [EditWars.ipynb]: This notebook contains the main analysis of this study. Here you will find the implementation of the topical distance model, as well as the analysis about cross-topical edit wars. 
* CreateWikiprojectGraph.ipynb: This a short notebook explaining how to create the [Wikiproject](https://en.wikipedia.org/wiki/Wikipedia:WikiProject) Graph. 
* Reverting behavior.ipynb: This notebook show the relationships among users' activity (number of contributions), reverts done, reverts received, and registration time (account age/tenure)
* Reverts from SHA1.ipynb: This notebook explains how we compute the reverts dataset. 




