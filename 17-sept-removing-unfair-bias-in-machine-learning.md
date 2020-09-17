---
description: 'https://odsc.com/speakers/removing-unfair-bias-in-machine-learning/'
---

# 17 Sept \(11:30 BST\) - Removing Unfair Bias in Machine Learning

[https://github.com/MargrietGroenendijk/gitbooks2/blob/master/files/odsc-bias-ml.ipynb](https://github.com/MargrietGroenendijk/gitbooks2/blob/master/files/odsc-bias-ml.ipynb)

AI can embed human and societal bias and be then deployed at scale. Many algorithms are now being reexamined due to illegal bias. So how do you remove bias & discrimination in the machine learning pipeline? In this workshop you will learn the debiasing techniques that can be implemented by using the open source toolkit AI Fairness 360.

AI Fairness 360 \(AIF360\) is an extensible, open source toolkit for measuring, understanding, and removing AI bias. It contains the most widely used bias metrics, bias mitigation algorithms, and metric explainers from the top AI fairness researchers across industry & academia.

### Session Outline

1. Introduction

2. Bias definitions

* 2.1 Bias and variance
* 2.2 Statistical vs. cognitive bias

3. AI fairness metrics

* 3.1 Install aif360 and import packages
* 3.2 Exploring data
* 3.3 Exploring bias

_Short break to discuss and chat in the slack channel_

4. Model building

* 4.1 Train on the original data

5. AI fairness algorithms

* 5.1 Pre-processing
* 5.2 In-processing
* 5.3 Post-processing

### Some house keeping

To go through the workshop material smoothly it will be easiest when we all use the same setup, especially as it will be harder to help you straight away when you might get stuck during this virtual event. Of course feel free to use your own local machine when you are comfortable with environments and installing missing packages to run the Jupyter notebook \(you can find the link below\).

{% hint style="warning" %}
I will try to help you when you have issues with the setup, but as time is limited during the workshop it is possible I have to do this later through the ODSC slack channels. Two of my fellow developer advocates will also be in the slack channel to help answer questions. I will be there for the full conference.
{% endhint %}

## Getting started

Start by setting up your free Cloud environment by following [these instructions](https://margriet-groenendijk.gitbook.io/odsc-2020/untitled).

When you have created a Project in Watson Studio the next step is to add a Jupyter notebook with the workshop content.

Click on **Add to project** at the top right.

![](.gitbook/assets/screenshot-2020-09-15-at-08.55.10.png)

 You will see the below menu with a list of all assets you can add. Click on **Notebook** to add one.

![](.gitbook/assets/screenshot-2020-09-03-at-10.56.21.png)

 This will bring you here, where you can create a new notebook, add one from a local file or from a URL:

![](.gitbook/assets/screenshot-2020-09-03-at-11.22.15.png)

To load the first notebook for this workshop, select **From URL**, give the notebook a name, paste the below link in the Notebook URL field and then click the Create button at the bottom right. You can leave the runtime as the default.  

`https://github.com/MargrietGroenendijk/gitbooks2/blob/master/files/odsc-bias-ml.ipynb`

### Running a notebook

Now a kernel is initialised and the notebook loaded:

![](.gitbook/assets/screenshot-2020-09-03-at-11.28.05.png)

Run each cell in order by selecting it, and then clicking the ▶︎ Run button at the top or use **Shift-Enter**. 

The notebook explores bias in a credit dataset. Find the original data [here](https://archive.ics.uci.edu/ml/datasets/Statlog+%28German+Credit+Data%29) and on [Kaggle](https://www.kaggle.com/uciml/german-credit). 

To go back to the notebook later, go to the Projects page and assets tab. Here you find the notebook. Click on the name to see the code, or the pencil to edit and run the notebook:

![](.gitbook/assets/screenshot-2020-09-03-at-12.00.01.png)

