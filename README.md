---
title: 
layout: post
weight: 10
hidden: true
---

===


**Course**: DS   <br/>
**Mod**: Mod 4 Sec 29 V2         <br/>
**Topic**:  Evaluating Classifiers  <br/>
**Amount of time**: 60 minutes <br/>
**Author**: 


***

#### Lesson Summary:

This lesson starts with reviewing precision and recall metrics. From there, accuracy and F1 scores are also investigated. Afterwards, confusion matrices are investigated to further demonstrate the concept of how to evaluate classification models in full detail. With this, there are numerous questions which you can pose to the class to check for and deepen students understanding. These questions begin with basic questions with reading confusion matrices and progress into more complex analysis and interpretation questions connecting confusion matrices to the previous precision, recall and accuraccy metrics introduced at the beginning of the lesson.

#### Topic:

Evaluating Classifiers

#### Learning goals for this lesson:

* Students will be able to compute the precision of a classifier from a raw confusion matrix.
* Students will be able to calculate the recall of a classifier from a raw confusion matrix.
* Students will be able to calculate the accuracy of a classifier from a raw confusion matrix.
* Students will be able to explain and interpret precions and recall metrics for a real world problem scenario.

#### Prerequisite knowledge:

* Students should have exposure to basic classifiers.

#### Prequisite Learn-Materials:

* [Linear to Logistic Regression](https://github.com/learn-co-curriculum/dsc-linear-to-logistic-regression)
* [Fitting a Logistic Regression Model - Lab](https://github.com/learn-co-curriculum/dsc-fitting-a-logistic-regression-model-lab)
* [Logistic Regression in SciKit Learn](https://github.com/learn-co-curriculum/dsc-logistic-regression-in-scikit-learn)
* [Logistic Regression in SciKit Learn - Lab](https://github.com/learn-co-curriculum/dsc-logistic-regression-in-scikit-learn-lab)

#### Post Learn-Materials:


* [Confusion Matrices](https://github.com/learn-co-curriculum/dsc-confusion-matrices)
* [Visualizing Confusion Matrices - Lab](https://github.com/learn-co-curriculum/dsc-visualizing-confusion-matrices-lab)
* [Evaluation Metrics](https://github.com/learn-co-curriculum/dsc-evaluation-metrics)
* [Evaluating Logistic Regression Models - Lab](https://github.com/learn-co-curriculum/dsc-evaluating-logistic-regression-models-lab)
* [ROC Curves and AUC](https://github.com/learn-co-curriculum/dsc-roc-curves-and-auc)

#### Relevant learning goals from Airtable: 

LOG_REG.1.recyRBEmTLshQgyXg
LOG_REG.2.recNcArTYAgqpfv58
LOG_REG.2.recut1Vi876iBkc4a
LOG_REG.3.reciKM6MVWzUInGJ8
LOG_REG.2.recut1Vi876iBkc4a
LOG_REG.2.recNcArTYAgqpfv58
LOG_REG.2.recNcArTYAgqpfv58
LOG_REG.1.recfDg1UPqrkWWtMF
LOG_REG.1.recgtlgpwtXagZMZ6
LOG_REG.3.rec0otLi6LZEqZBpC

#### Materials

* Ipython notebook

#### Vocab / Concepts 

* Precision
* Recall
* F1 Score
* Accuracy
* Confusion Matrix

#### Lesson Outline:

* Precision Vs Recall (5 minutes)
	* Useful Example: A naive classifier that always arbitrarily predicts 'No' for whether a patient has a rare disease will have an accuracy of 99.9% if only .1% of the sample population actually does have the disease. That said, it will have a recall rate of 0%. Because of class imbalance or the varied cost associated with false positives versus false negatives, alternative evaluation metrics such as precision and recall are needed.
* F1 / F$/bett$ Scores (5 minutes)
* Confusion Matrix (10 minutes)
	* Analogy to punnett squares (may activate prior knowledge from student's high school biology classes)

	* Interpretation Questions for ResNet-50 Confusion Matrix:
		* Which letters were most successfully predicted by this classifier? (C and F; 97% accuracy, B and W with 95% accuracy)
* Plotting Confusion Matrices with Matplotlib (20 minutes)
	* What is the precision for the Versicolor species? (100%)
	* What is the recall for the Versicolor species? (62%)
	* What is the accuracy for the Versicolor species? (62%)
	* What is the overall accuracy of the classifier? (13+10+9)/(13+10+6+9)= 32/38 = 84.211%
	* What is the recall rate for the Virginica species? (100%)
	* What is the precision rate for the Virginica species? 9/(9+6) = 9/15 = .6 = 60%
	* How are the entries for the normalized confusion matrix calculated? (Divided by the total number for each true label; rows sum to 100%.)
	* Comment out lines 7- through 78 and rerun the code cell. What do you notice?
	* Explain line 76.

