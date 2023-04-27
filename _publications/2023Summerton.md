---
title: "Outlier detection of vital sign trajectories from COVID-19 patients"
collection: publications
permalink: /publication/2023Summerton
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2023-07-22
venue: 'Proc. of IEEE EMBC 2023, Sydney'
paperurl: 'http://academicpages.github.io/files/2023Summerton.pdf'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
In this work, we present a novel trajectory comparison
algorithm to identify abnormal vital sign trends, with
the aim of improving recognition of deteriorating health.
There is growing interest in continuous wearable vital
sign sensors for monitoring patients remotely at home. These
monitors are usually coupled to an alerting system, which is
triggered when vital sign measurements fall outside a predefined
normal range. Trends in vital signs, such as increasing heart
rate, are often indicative of deteriorating health, but are rarely
incorporated into alerting systems.

We introduce a dynamic time warp distance-based measure
to compare time series trajectories. We split each multi-variable
sign time series into 180 minute, non-overlapping epochs. We
then calculate the distance between all pairs of epochs. Each
epoch is characterized by its mean pairwise distance (average
link distance) to all other epochs, with clusters forming with
nearby epochs.

We demonstrate in synthetically generated data that this
method can identify abnormal epochs and cluster epochs with
similar trajectories. We then apply this method to a real-world
data set of vital signs from 8 patients who had recently been
discharged from hospital after contracting COVID-19. We show
how outlier epochs correspond well with the abnormal vital
signs and identify patients who were subsequently readmitted
to hospital.

[Download paper here](http://academicpages.github.io/files/2023Summerton.pdf)

Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1).