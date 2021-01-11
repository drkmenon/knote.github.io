---
date: "2019-05-05T00:00:00+01:00"
draft: false
linktitle: Funnel plot
menu:
  Orthopaedic Notes:
    parent: Basic Science
    weight: 1
title: Funnel plot
toc: true
type: docs
weight: 2
---

{{% callout note %}}
This is all you have to know for your FRCS exam
{{% /callout %}}

Funnel plot and its statistical basis

**Introduction**
 
**Funnel plot** is a common question for FRCS(Tr & Orth) viva. To understand the concept, we have to give some thought in to the basis of this statistical tool. Let us start from the very base.

Mean, median, and mode are three kinds of "averages". There are many "averages" in statistics, but these are most common.

**"mean"** is a statistical "average", where you add up all the variables and then divide by the number of variables.

The **"median"** is the **"middle"** value in the list of variables. To find the median, your variables have to be listed in numerical order from smallest to largest, so you may have to rewrite your list before you can find the median. 

The **"mode"** is the value that occurs most often. If no variable in the list is repeated, then there is no mode for the list.

To understand funnel plot we should also know the statistical concepts of  *variance* , *standard deviation* and *standard error of mean*.

### Variance
* **It is the sum of average squared difference of mean**.

eg: x~1, x~2, x~3, x~n are a list of *n* number of values, then  mean, x̄ = (x~n + x~1 )/n. Then the **Variance**=Σ (x-x̄)^2/ (n-1).

### Standard deviation
* It is the measure of standardized dispersion of data from the mean. It is calculated by taking the square root of variance.

Standard deviation  σ = √∑, i.e., standard deviation is the square root of variance. 

Assume that someone is asked to walk on a straight line from point *a* to point *b*. The individual steps taken by the person can be equated to standard deviation and the variance is the deviation of the path from the central line.

![walking with variance and sd](/img/funnel.png)


> Unlike standard deviation **variance** can identify the outliers and also shows the spread of the data.

### standard error of mean(SEM)
* It is the standard deviation of the sample mean from the population mean.  
Assume that there is a population of 1000 members. In order to study the average height of the population, we have to select a sample size. Also assume that one scientist *y* started a study with a sample size of 50. He repeated the study for *n* times. He found that each time the average height found out from the study was different. He calculated the mean value of the height from these *n* studies and designated it as x̄~1. This x̄~1 is the **sample mean** for his study. 

Another scientist *z* selected a sample size of 10 and conducted *n* number of similar study and similarly he also got a sample mean, x̄~2. 
So they decided to find out the actual population mean x̄ by studying the entire population. They also calculated how far the x̄~1 and x̄~2 deviate from x̄. The deviation of x̄~1 was found to be less than x̄~2. This deviation is called **Standard error of mean**

> when *n* increases,  **standard error of mean** decreases and the precision of the study increases.

*This is the basis of **funnel plot**.*

### Funnel plot 
It is a representation of **SEM** plotted against the true population mean or the no effect line of a study in a graph. Smaller studies tend to have larger SEM and the larger studies will have smaller SEM.  Hence the plot assumes a funnel shape. I an ideal world, **funnel plot** is supposed to form a symmetrical "funnel". This is not the case in real world, because of various reasons.

### Uses of funnel plot
* To identify outliers. Eg: A surgical resident's performance
* To identify the validity of a meta-analysis. An asymmetrical funnel plot suggests a potential problem with the results of the meta-analysis.
### Causes of asymmetrical  funnel plot
1. Reporting bias
 	* Reporting bias
 		* Publication bias: Delayed reporting, language bias, duplication)
 		* Selective outcome reporting
 		* Selective analysis reporting
 2. Poor methodology
 	* Design
 	* Analysis
 	* Fraud
 3. Heterogeneity
 4. Chance
 
 ### Heterogeneity 
**Variations over and above that is expected by chance** 
* predicts whether the data from different studies can be combined for meta-analysis to obtain a forest plot.
### Causes
|Clinical|Statistical|
|-|-|
|Difference in the population|Individual results are inconsistent |
|Difference in the study design|Difference in size of benefit |
|Difference in intervention|Difference in size of harm|
|Difference in outcome| |
|Always present| |
|Cannot be statistically evaluated |Can be evaluated statistically| 

### Detecting Heterogeneity 
* Review the table describing individual studies
* "eye ball test", review the forest plot
* Review the statistical tests
* Statistical tests

### Statistical tests for detecting heterogeneity 
* Tests for its presence: Chi Square test, p>0.1 means study is homogenous 
* Test to quantify: I^2 
	* It measures the % of heterogeneity (≤25%––low, 50%––moderate, ≥75%––high)
	
### Once heterogeneity is identified and quantified, he have to analyze and find out why it is present

### This is done by
* subgroup analysis
* Metaregression








