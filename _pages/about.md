---
permalink: /
title: "Boyan Duan"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Data Scientist working at Google. My current work focus on ad performance and data-driven attribution. Before that, I got my Ph.D. degree in the Department of [Statistics & Data Science at Carnegie Mellon University](http://stat.cmu.edu). I was very fortunate to be advised by professor [Aaditya Ramdas](http://www.stat.cmu.edu/~aramdas/) and professor [Larry Wasserman](http://www.stat.cmu.edu/~larry/). We worked on developing interactive methodologies that leverage machine and human intelligence for various hypothesis testing problems. Here is my [thesis](https://duanby.github.io/files/boyan_defense_latex.pdf).

Here is my [Curriculum Vitae](https://duanby.github.io/files/cv.pdf). 


Education
=======
* Ph.D. in Statistics, 2021
: Carnegie Mellon University, Pittsburgh, USA

* B.S. in Statistics, 2016
: University of Science and Technology of China, Hefei

* Intern in Computer Science, 2015
: University of Birmingham, UK


Research Interests
======
* Human-in-the-loop interactive testing

* Multiple testing and nonparametric testing

* Causal inference: identifications under heterogeneous treatment effect

* Reproducibility in science and technology


Papers and submissions
=======
* Interactive Martingale Tests for the Global Null <small> (EJS, 2020) [arxiv,](https://arxiv.org/pdf/1909.07339.pdf) [code](https://github.com/duanby/interactive-martingale)</small>
: **Boyan Duan, Aaditya Ramdas, Sivaraman Balakrishnan, Larry Wasserman**
: Global null testing is a classical problem going back about a century to Fisher’s and Stouffer’s
combination tests. We present simple martingale analogs of these classical tests,
which are applicable in two distinct settings: (a) the online setting in which there is a possibly
infinite sequence of p-values, and (b) the batch setting, where one uses prior knowledge to preorder
the hypotheses. Built on the martingale analogs, we use a recent idea of “masking” p-values to develop a novel interactive test for the global null. It can take advantage of covariates and repeated user guidance to create a data-adaptive ordering that achieves higher detection power against structured alternatives.

* Familywise error rate control by interactive unmasking <small>(ICML, 2020) [arxiv,](https://arxiv.org/pdf/2002.08545.pdf) [code,](https://github.com/duanby/i-FWER) [talk](https://icml.cc/virtual/2020/poster/6595)</small>
: **Boyan Duan, Aaditya Ramdas, Larry Wasserman**
: We propose a method for multiple hypothesis testing with familywise error rate (FWER) control, called the i-FWER test. Most testing methods are predefined algorithms that do not allow modifications after observing the data. However, in practice, analysts tend to choose a promising algorithm after observing the data; unfortunately, this violates the validity of the conclusion. The i-FWER test allows much flexibility: a human (or a computer program acting on the human's behalf) may adaptively guide the algorithm in a data-dependent manner. We prove that our test controls FWER if the analysts adhere to a particular protocol of "masking" and "unmasking". We demonstrate via numerical experiments the power of our test under structured non-nulls and then explore new forms of masking.


* Interactive rank testing by betting <small>(Conference on Causal Learning and Reasoning, 2022) [arxiv,](https://arxiv.org/pdf/2009.05892.pdf) [code](https://github.com/duanby/interactive-rank) </small>
: **Boyan Duan, Aaditya Ramdas, Larry Wasserman**
: In order to test if a treatment is perceptibly different from a placebo in a randomized experiment with
covariates, classical nonparametric tests based on ranks of observations/residuals have been employed
(eg: by Rosenbaum), with finite-sample valid inference enabled via permutations. This paper proposes
a different principle on which to base inference: if — with access to all covariates and outcomes, but
without access to any treatment assignments — one can form a ranking of the subjects that is sufficiently
nonrandom (eg: mostly treated followed by mostly control), then we can confidently conclude that there
must be a treatment effect. Based on a more nuanced, quantifiable, version of this principle, we design an
interactive test called i-bet: the analyst forms a single permutation of the subjects one element at a time,
and at each step the analyst bets toy money on whether that subject was actually treated or not, and
learns the truth immediately after. The wealth process forms a real-valued measure of evidence against
the global causal null, and we may reject the null at level α if the wealth ever crosses 1/α.

* Data fission: splitting a single data point <small>(JASA, 2023. Discussion paper.) [arxiv](https://arxiv.org/pdf/2112.11079)</small>
: **James Leiner, Boyan Duan, Larry Wasserman, Aaditya Ramdas**
: Suppose we observe a random vector X from some distribution in a known family with unknown
parameters. We ask the following question: when is it possible to split X into two pieces f(X)
and g(X) such that neither part is sufficient to reconstruct X by itself, but both together can
recover X fully, and their joint distribution is tractable? One common solution to this problem
when multiple samples of X are observed is data splitting, but Rasines and Young (2022) offers
an alternative approach that uses additive Gaussian noise — this enables post-selection inference
in finite samples for Gaussian distributed data and asymptotically when errors are non-Gaussian.
In this paper, we offer a more general methodology for achieving such a split in finite samples by
borrowing ideas from Bayesian inference to yield a (frequentist) solution that can be viewed as
a continuous analog of data splitting. We call our method data fission, as an alternative to data
splitting, data carving and p-value masking. We exemplify the method on several prototypical
applications, such as post-selection inference for trend filtering and other regression problems, and
effect size estimation after interactive multiple testing.

* Interactive identification of individuals with positive treatment effect while controlling false discoveries <small>(Journal of Causal Inference, 2024) [arxiv,](https://arxiv.org/pdf/2102.10778.pdf) [code,](https://github.com/duanby/I-cube) [talk](https://www.selectiveinferenceseminar.com/past-talks) </small>
: **Boyan Duan, Larry Wasserman, Aaditya Ramdas**
: Out of the participants in a randomized experiment with anticipated heterogeneous treatment effects, is it possible to identify which ones have a positive treatment effect, even though each has only taken either treatment or control but not both? While subgroup analysis has received attention, claims about individual participants are more challenging. We frame the problem in terms of multiple hypothesis testing: we think of each individual as a null hypothesis (the potential outcomes are equal, for example) and aim to identify individuals for whom the null is false (the treatment potential outcome stochastically dominates the control, for example). We develop a novel algorithm that identifies such a subset, with nonasymptotic control of the false discovery rate (FDR). Our algorithm allows for interaction — a human data scientist (or a computer program acting on the human’s behalf) may adaptively guide the algorithm in a data-dependent manner to gain high identification power. We also propose several extensions: (a) relaxing the null to nonpositive effects, (b) moving from unpaired to paired samples, and (c) subgroup identification. We demonstrate via numerical experiments and theoretical analysis that the proposed method has valid FDR control in finite samples and reasonably high identification power.


Previous Projects
=======
Although not related to my current research interests, I did some projects in previous years.

* Perception of security over time in the Democratic Republic of Congo
: **with Robin Mejia, Anjali Mazumder, Patrick Vinck, Phuong Pham**
: Over the past decades, there has been continuous armed conflict and economic and political instability in the Democratic Republic of the Congo (DRC). Despite the effort made by the Congolese government to rebuild the country and the ongoing United Nations peacekeeping mission, there has been little improvement in terms of peace and justice. In discussions, Vinck noted that conflicts in Congo are often described as ethnic conflicts, despite a lack of formal study to assess this description. To examine the evolution of the conflict, we study the changing pattern of the population's perception of security and ethnic relations and uncover regions and subpopulations with different trends.

* The automatic generation of semantic environment maps from robot sensor data
: **with Lars Kunze**
: During my undergraduate internship, I participated in an international research project on robotics for long-term autonomy in mobile robots involving six European universities, called [STRANDS](http://strands.acin.tuwien.ac.at/). We use simple machine learning algorithms to interpret sensor data from the robots, such as identifying objects, recognizing the space to move freely, classifying the types of rooms, etc. It was an exciting experience for me to get involved with research on robotics for the first time.

Teaching Assistant
=======
In-class tutorials, office hours, and grading for the following classes in Carnegie Mellon University:
* 36-218 Probability Theory for Computer Scientists (Head TA)
* 36-708 Statistical Methods in Machine Learning (Ph.D. Level)
* 36-705 Intermediate Statistics (Ph.D. Level)
* 46-927  Statistical Machine Learning II
* 36-410 Introduction to Probability Modeling
* 36-401 Modern Regression
* 36-217 Probability Theory and Random Processes
* 36-225 Introduction to Probability Theory
