# Project 4: Machine Learning Fairness

### [Project Description](doc/project4_desc.md)

Term: Spring 2022

+ Team 7
+ Projec title: Machine Learning Fairness (DM/DM-sen vs PR)
+ Team members
	+ Shintaro Nakamura (sn2904@columbia.edu)
	+ Jiazheng Chen (jc5656@columbia.edu)
	+ Fucheng Liu (fl2564@columbia.edu)
	+ Xiangyu Ma (xm2258@columbia.edu)
	+ Nichole Zhang (qz2446@columbia.edu)

+ **Project summary**: Machine Learning fairness is an established area of machine learning to ensure model fairness for certain groups or individuals by minimizing biases derived from data and correcting inaccuracies of model predictions. Two different algorithms from the published papers were implemented and compared to determine which algorithm is more fair. The data, that contains the criminal history, jail, prison time, demographics and so forth, is used for the ML algorithms to predict criminal defendants' likelihood to re-offend.

	+ Algorithm 4: [Fairness Beyond Disparate Treatment & Disparate Impact: Learning Classification without Disparate Mistreatment (DM and DM-sen)](https://arxiv.org/abs/1610.08452)
	+ Algorithm 5: [Fairness-aware Classifier with Prejudice Remover Regularizer (PR)](https://link.springer.com/chapter/10.1007/978-3-642-33486-3_3)
	+ Data used: [compas-scores-two-years.csv](https://www.propublica.org/datastore/dataset/compas-recidivism-risk-score-data-and-analysis)

+ **Technologies used**: Python (sklearn, cvxpy, dccp, torch, scipy, numpy, pandas)

**Contribution statement**: All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. 

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
