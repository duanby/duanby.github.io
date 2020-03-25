---
permalink: /
title: "Boyan Duan"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Ph.D. student in the Department of [Statistics & Data Science at Carnegie Mellon Univeristy](http://stat.cmu.edu). I am very fortunate to be advised by professor [Aaditya Ramdas](http://www.stat.cmu.edu/~aramdas/) and professor [Larry Wasserman](http://www.stat.cmu.edu/~larry/). We work on developing interactive methodologies that leverage machine and human intelligence for various hypothesis testing problems.

Here is my [Curriculum Vitae](https://duanby.github.io/files/cv.pdf).


Education
=======
* Ph.D. in Statistics, 2021 (expected)
: Carnegie Mellon University, Pittsburgh, USA

* B.S. in Statistics, 2016
: University of Science and Technology of China, Hefei

* Intern in Computer Science, 2015
: University of Birmingham, UK


Research Interests
======
* Human-in-the-loop interactive testing

* Multiple testing

* Nonparametric testing

* Reproducibility in science and technology


Submission and Ongoing Projects
=======
* [Interactive Martingale Tests for the Global Null](https://arxiv.org/pdf/1909.07339.pdf)
: **Boyan Duan, Aaditya Ramdas, Sivaraman Balakrishnan, Larry Wasserman**
: Global null testing is a classical problem going back about a century to Fisher’s and Stouffer’s
combination tests. We present simple martingale analogs of these classical tests,
which are applicable in two distinct settings: (a) the online setting in which there is a possibly
infinite sequence of p-values, and (b) the batch setting, where one uses prior knowledge to preorder
the hypotheses. Built on the martingale analogs, we use a recent idea of “masking” p-values to develop a novel interactive test for the global null, which can take advantage of covariates and repeated user guidance to create a data-adaptive ordering that achieves higher detection power against structured alternatives.

* [Familywise error rate control by interactive unmasking](https://arxiv.org/pdf/2002.08545.pdf)
: **Boyan Duan, Aaditya Ramdas, Larry Wasserman**
: We propose a method for multiple hypothesis testing with familywise error rate (FWER) control, called the i-FWER test. Most testing methods are predefined algorithms that do not allow modifications after observing the data. However, in practice, analysts tend to choose a promising algorithm after observing the data; unfortunately, this violates the validity of the conclusion. The i-FWER test allows much flexibility: a human (or a computer program acting on the human's behalf) may adaptively guide the algorithm in a data-dependent manner. We prove that our test controls FWER if the analysts adhere to a particular protocol of "masking" and "unmasking". We demonstrate via numerical experiments the power of our test under structured non-nulls, and then explore new forms of masking.


* Interactive rank tests (ongoing)
: **Boyan Duan, Aaditya Ramdas, Larry Wasserman**
: In a nonparametric setting where the underlying distribution is unknown, classical tests to compare multiple samples are based on the ranking of the observations, such as the Wilcoxon signed-rank test. We propose rank tests that adjust for covariates in an interactive manner: a human analyst may adaptively design and adjust the algorithm using observed data, covariates, domain knowledge of any form, etc. We developed the interactive rank tests for several nonparametric testing problems: comparing two/multiple samples with paired/unpaired data.  Shown by numerical experiments, theoretical power analysis, and a real data application of comparing two medical treatments, the interactive rank tests have higher power than the classical tests when the difference between samples exists only in a small subpopulation.

Previous Projects
=======
Although not related to my current research interests, I did some interesting projects in previous years.

* Perception of security over time in Democratic Republic of Congo
: **with Robin Mejia, Anjali Mazumder, Patrick Vinck, Phuong Pham**
: Over the past decades, there has been continuous armed conflict and economic and political instability in the Democratic Republic of the Congo (DRC). Despite the effort made by the Congolese government to rebuild the country and the ongoing United Nations peacekeeping mission, there has been little improvement in terms of peace and justice. In discussions, Vinck noted that conflicts in Congo are often described as ethnic conflicts, despite a lack of formal study to assess this description. To examine the evolution of the conflict, we study the change pattern of population's perception of security and ethnic relations, and uncover regions and subpopulations with different trends.

* The automatic generation of semantic environment maps from robot sensor data
: **with Lars Kunze**
: During my undergraduate internship, I participated in a international research project on robotics for long-term autonomy in mobile robots involving six European universities, called [STRANDS](http://strands.acin.tuwien.ac.at/). We use simple machine learning algorithms to interpret sensor data from the robots, such as identifying objects, recognizing the movable space, classifying the types of rooms, etc. It was an exciting experience for me to get involved with research on robotics for the first time.

Teaching Assistant
=======
In-class tutorials, office hours and grading for the following classes in Carnegie Mellon University:
* 36-218 Probability Theory for Computer Scientists (Head TA)
* 36-708 Statistical Methods in Machine Learning (PhD Level)
* 36-705 Intermediate Statistics (PhD Level)
* 46-927  Statistical Machine Learning II
* 36-410 Introduction to Probability Modeling
* 36-401 Modern Regression
* 36-217 Probability Theory and Random Processes
* 36-225 Introduction to Probability Theory
