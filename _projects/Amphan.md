---
title: 'Amphan - Analyzing Experiences of Extreme Weather Events using Online Data'
collection: projects
excerpt: 'The DSSG Solve team, in collaboration with the International Water Management Institute (IWMI), aims to develop research methodologies that leverage online social media data to better understand the experiences and needs of vulnerable communities affected by natural disasters. This research tool would enable users to tap into the online discourse and social, political, and economic effects of extreme weather events. Through our goal, we hope to derive actionable insights to supplement on-the-ground efforts and help inform critical policy-making processes.'
permalink: /projects/Amphan
---

Objective
------
For the initial phase, we focus on a recent extreme weather event - Cyclone Amphan, which made landfall in South Asia on May 20, 2020, and affected 18 million people along the way. We first aimed to characterize how collective knowledge about Cyclone Amphan was produced on Twitter. Accordingly, our first research question was: Who and which ideas are shaping the narratives around Cyclone Amphan, and whose experiences are going unheard? Next, we aimed to explore how to best support people affected by extreme weather events. This led to our second research question: Can Twitter content help identify unmet needs of people affected by Cyclone Amphan? If so, how?

Research Methods
--------------

<b>Identifying narratives and influential users</b>

![alt RQ1](http://kanav-mehra.github.io/images/rq1_pipeline.jpg)

<b>Approach</b>:
We begin by identifying the topics discussed in each tweet by assigning labels via zero-shot text classification. In order to highlight tweets from users who were personally affected by Cyclone Amphan, the data is then filtered to include only first person tweets using the point-of-view analysis. We narrow down our focus to the labels that have a median negative sentiment with the assumption that negative experiences are more likely to suggest unmet needs. We then report representative tweets using extractive summarization techniques to identify the dominant themes within each label.


<b>Identifying negative experiences and unmet needs</b>

![alt RQ2](http://kanav-mehra.github.io/images/rq2_pipeline.jpg)

<b>Approach</b>:
We address this question through the usage of user vectors as a means of positioning users in a two dimensional space. The network's edges are assigned based on the number of retweets and/or replies among users. These users can now be grouped into different communities using two different methods: 1) discourse-based, where the clustering is done on the embedding features and 2) community-based, done through network clustering methods. For both clustering methods, the most popular users within each cluster are identified based on centrality measures and the number of followers the user has.

Project Partners
------
* [International Water Management Institute (IWMI)](https://www.iwmi.cgiar.org/)
* [DSSG Solve for Good](https://solveforgood.org/)

Useful Links
------
* [Github Repository](https://github.com/kanav-mehra/solve-iwmi)
* [Project Webpage](https://solveforgood.org/proj/35/)
* [Study on the impact of cyclone Amphan (Developed by IWMI)](https://www.iwmi.cgiar.org/2020/05/using-maps-to-save-lives-when-a-super-cyclone-strikes/)
* [arXiv preprint](https://kanav-mehra.github.io/publication/Amphan-2020)
* [Data Fest 2020 Presentation](https://www.youtube.com/watch?v=YtKYIS61i5I)

DSSG Solve Team
-----
<i>Kanav Mehra</i>, Ancil Crayton, João Fonseca, Jared Ross, Marcelo Sandoval-Castañeda

IWMI Team
-----
Michelle Ng, Rachel von Gnechten