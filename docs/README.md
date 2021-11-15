---
layout: home
permalink: index.html

# Please update this with your repository name and title
repository-name: eYY-4yp-project-template
title:
---

[comment]: # "This is the standard layout for the project, but you can clean this and use your own template"

# Project Title

#### Team

- E/15/092, Imesh Ekanayake, [email](mailto:imeshuek@eng.pdn.ac.lk)
- E/15/187, Devin Kulanjith, [email](mailto:kulanjith.gallage@eng.pdn.ac.lk)

#### Supervisors

- Dr. Dhamayanthi Herath, [email](mailto:damayanthiherath@eng.pdn.ac.lk)
- Dr. Upul Jayasinghe, [email](mailto:upuljm@eng.pdn.ac.lk)
- Dr. Kasun Amarasinghe, [email](mailto:amarasinghe@cmu.edu)

#### Table of content

1. [Abstract](#abstract)
2. [Related works](#related-works)
3. [Methodology](#methodology)
4. [Experiment Setup and Implementation](#experiment-setup-and-implementation)
5. [Results and Analysis](#results-and-analysis)
6. [Conclusion](#conclusion)
7. [Links](#links)

---

## Abstract
Machine Learning (ML) has contributed to many advances in science and technology.  Recently a trend of applications in high-stake decision-making has been initiated. The development of ML made the decision-making process unclear with complex black-box models, especially the state-of-the-art models which have maximized the performance are more complex, inexplicable, and hard to explain. On the contrary, high-stakes settings as healthcare, finance, and criminal justice, have strict ethical concerns that made a mandatory requirement to explain each decision or the model as a whole. Besides, the acts and regulations like General Data Protection Regulation (GDPR)  make it obligatory to explain the decisions made by computer systems and became a social right to explanation.One of the most pressing problems in this field is explainability and interpretability of the decisions which are made by the several algorithms Moreover, it is necessary to ensure the fairness and transparency of a decision to obtain the stakeholders' trust. The theoretical knowledge of explainable machine learning is not well-tested on real-world problems with direct social impact. In this paper, we have identified a quandary that reflects the characteristics of a high-stakes machine learning problem in the public sector. An early warning system to predict and help the projects that could be unfunded in an educational crowdfunding platform in a resource-constrained environment has been presented.

## Related works

## Methodology

## Experiment Setup and Implementation

## Results and Analysis

## Conclusion

Even though the machine learning became one of the hot topics in current days in almost all the fields, trust, transparency and fairness of the predictive models has not been properly considered. In high stake settings, where it makes a direct impact on people's lives or future of a business it is important to obtain the trust of the domain experts to use the model predictions in decision making process. In the above workflow, we have trained 8 machine learning algorithms in periodic manner using cohort concept and designed  a grid search for the time series data to optimize without having a data leakage. Next, we  obtained the overall performance of the predictions to select the best performing models. Once those models were selected the top-K (here we have taken K as 100) recall has been measured to select the best predictive model for the task and selected CatBoost model for further analysis.
Next we have used explainable AI models (SHAP and LIME) analyse individual analysis of the predictions, there we obtained the importance of each attribute separately for the prediction of each instance. Once the top-k,  middle-K and bottom-k importance of attributes are selected, then values are normalized for each instance (addition of importance become 1 in each instance).  Finally the correlation, of the normalized importance with the actual values have been considered and identified the distribution of actual values along with the importance variation.

In conclusion, the final machine learning model has adhere to the thinking pattern of users and domain experts can use the explanation to improve the project quality using the insights of the model.

## Links

[//]: # ( NOTE: EDIT THIS LINKS WITH YOUR REPO DETAILS )

- [Project Repository](https://github.com/cepdnaclk/repository-name)
- [Project Page](https://cepdnaclk.github.io/repository-name)
- [Department of Computer Engineering](http://www.ce.pdn.ac.lk/)
- [University of Peradeniya](https://eng.pdn.ac.lk/)

[//]: # "Please refer this to learn more about Markdown syntax"
[//]: # "https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet"
