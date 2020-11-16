---
title: 'SMERP Data Challenge Track - ECIR 2017'
collection: projects
excerpt: 'The motivation of the data challenge is to promote development of IR methodologies that can be used to extract important information from social media during emergency events, and to arrange for comparative evaluation of the methodologies.'
permalink: /projects/SMERP
---

Objective
------
The [SMERP Data Challenge](https://www.computing.dcu.ie/~dganguly/smerp2017/), organized by the 39th European Conference on Information Retrieval (ECIR 2017), was about extracting and summarizing information relevant to a set of practical information needs (topics) that are critical for post-disaster relief operations, such as need and availability of resources, infrastructure damage and restoration, etc. Specifically, each topic was shared in TREC format - including a title, a brief description, and a more detailed narrative on what type of tweets will be considered relevant to the topic. The track used a [dataset](https://zenodo.org/record/3336563#.X5cDE4gzZPZ) of microblogs posted during the August 2016 earthquake in central Italy.

Approach
------
We demonstrate that topic-wise summarization of tweets during disaster events can be better accomplished by initially summarizing the tweets using some basic summarizer, then categorizing the relevant and non-relevant tweets, and finally summarizing again. We present a semi-automatic extractive summarization method that exploits a combination of [SumBasic Summarizer]( https://github.com/EthanMacdonald/SumBasic) and different classifiers to summarize the topic wise relevant microblogs (tweets) extracted through manually identified query-term matching. Acordingly, our method obtained the overall <b>first place</b> in the SMERP 2017 Data Challenge - Summarization Track, highlighting that it is an effective approach in summarizing tweets in a disaster scenario and can be replicated across diverse domains.

Useful Links
------
* [Data Challenge Webpage](https://www.computing.dcu.ie/~dganguly/smerp2017/)
* [Results of Text Summarization Sub-Track](https://www.computing.dcu.ie/~dganguly/smerp2017/SMERP-Summarization-Track-document.pdf)
* [Dataset](https://zenodo.org/record/3336563#.X5cDE4gzZPZ)
* [Workshop Paper](https://kanav-mehra.github.io/publication/SMERP-2017)