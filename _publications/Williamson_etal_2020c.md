---
title: "A Source Clustering Approach for Efficient Inundation Modeling and Regional Scale PTHA"
collection: publications
permalink: /publications/Williamson_etal_2020c
#excerpt: ''
date: 2020-10-20
venue: 'Frontiers in Earth Science'
paperurl: 'http://amy-l-williamson.github.io/files/Williamson_etal_2020c.pdf'
---

In this study, we present an approach to estimating inundation depth probabilities (in the form of hazard curves at a set of coastal locations)that consists of two components. The first component uses a Karhunen-Loe`ve expansion to express the probability density function (PDF) for all possible events with PDF parameters that are geophysically reasonable for the Cascadia Subduction Zone (CSZ). It is then extremely easy and computationally cheap to generate a very large N number of samples from this PDF; doing so and performing a full tsunami inundation simulation for each provides a brute force approach to estimating probabilities of inundation. The estimate is simply the number of random realizations that reach specified inundation depth divided by N. However, to obtain reasonable results, particularly for extreme flooding due to rare events, N would have to be so large as to make the necessary tsunami simulations prohibitively expensive. The second component tackles this difficulty by using importance sampling techniques to ensure we adequately sample the tails of the distribution and properly re-weight the probability assigned to the resulting realizations, and by grouping the realizations into a small number of clusters that we believe will give similar inundation patterns in the region of interest.



[You can read this paper here.](http://amy-l-williamson.github.io/files/Williamson_etal_2020c.pdf)

Recommended citation: Williamson, A., Rim, D., Adams, L., LeVeque, R. J., Melgar, D., & Gonzalez, F. (2020). A Source Clustering Approach for Efficient Inundation Modeling and Regional Scale PTHA. Frontiers in Earth Science, 8 (2020) p. 442.
