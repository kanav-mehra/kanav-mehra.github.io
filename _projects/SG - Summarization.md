---
title: 'Summarization of Microblogs for Disaster and Emergency Preparedness'
collection: projects
excerpt: 'Our goal was to analyze existing extractive summarization algorithms and devise novel methods for summarizing the large volumes of microblogs (tweets) posted during disaster events with implications for relief efforts.<br />
<b>Advisor</b>: Dr. Saptarshi Ghosh, IIT Kharagpur, India.'
permalink: /projects/Summarization
---

Objective
------
Microblogging sites, notably Twitter, have become important sources of real-time situational information during emergency events. On such sites, microblogs are usually posted so rapidly and in such large volumes, that it is not feasible for human users to go through all the posts. In such scenarios, summarization of microblogs (tweets) is an important task. In this project, we study the performance of <i>eight</i> off-the-shelf extractive summarization algorithms and propose novel ensemble techniques for text summarization. We demonstrate that it is possible to combine off-the-shelf summarization algorithms to achieve better summarization for microblogs.<br />
<b>Advisor:</b> [Prof. Saptarshi Ghosh](https://sites.google.com/site/saptarshighosh/) 

Approach
------

<b>Comparing extractive summarization algorithms:</b>
We compared and evaluated eight off-the-shelf extractive summarization algorithms over microblogs posted during five recent disaster events, based on a standard metric for automatic evaluation - ROUGE. Given the same input set of microblogs, these summarization algorithms generated vastly diverse summaries with minimal overlap. 
For more information, check out the paper [here](https://kanav-mehra.github.io/publication/IEMIS-2018).

<b>Developing Ensemble algorithms for summarization:</b>
As the base summarization algorithms worked on different principles and produced diverse summaries, we further extended this research to propose ensemble schemes that combine their outputs to generate better quality, multi-faceted summaries. In the unsupervised ensemble algorithm, we constructed a graph that groups the tweets according to different similarity measures and selects a representative tweet from each group while minimizing redundancy. Furthermore, in the supervised ensemble approach, we used Learning-to-Rank algorithms to learn a mechanism to rank tweets in order of importance, based on the rankings computed by different base algorithms.
For more information, check out the paper [here](https://kanav-mehra.github.io/publication/Ensemble-2018).

<b>Datasets:</b>
The experimental setup for application of these algorithms consisted of tweets posted during recent disaster events – The February 2013 Hyderabad Blasts, The Typhoon Hagupit in Philippines, The Sandy Hook school shooting in USA, The April 2015 Nepal Earthquake and Floods in Uttaranchal, India.