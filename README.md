![]()

# Machine-Learning-and-Statistics-Winter-21-22


# i) Introduction

This GitHub repository contains two Jupyter notebooks relating to the following Python libraries;

1) `scikit-learn`
2) `scipy.stats`

<br/>

There are separate sections for each of the aforementioned Python libraries included in this README. Each section includes the objectives for that notebook and details how these objectives are met.

Along with the README and the two notebooks there are data files, image files and other related files included in the repository. This content forms 100% of the marks for the module "Machine Learning and Statistics in Winter 2021/2022". 

Also included in this README are instructions on how to install the required packages and how to run the notebooks after the packages have been installed.

<br/>

## ii) Instructions on installing required packages


<br/>
<br/>

## iii) Instructions on how to use this project

- `name of notebook 1`
- `name of notebook 2`

<br/>
<br/>


## iv) Repository overview


<br/>
<br/>

# 1) scikit-learn Jupyter Notebook

## Notebook objectives
<br/>

* Provide a clear and concise overview of the scikit-learn Python library.
* Provide demonstrations of three interesting scikit-learn algorithms. You may choose these yourself, based on what is covered in class or otherwise. Note that the demonstrations are at your discretion – you may choose to have an overall spread of examples across the library or pick a particular part that you find interesting.
* Appropriate plots and other visualisations to enhance your notebook for viewers.

<br/>

This notebook starts out with an overview of the scikit-learn Python library; what it is, where it came from and where and why it is used. The following section details machine learning and it's relationship to artificial intelligence and computer science. Where machine learning is used, how common it has become and how it's used on a daily basis across everything from streaming platforms to banks and social media is discussed.

Technical aspects of machine learning such as the supervised and unsupervised approaches are discussed before looking at machine learning algorithms in scikit-learn. Three scikit-learn algorithms are then discussed and demonstrated:

* `LinearRegression()`
* `RandomForestClassifier()`
* `KNeighborsClassifier()`

With the introduction complete and some background on machine learning along with the selection of three scikit-learn algorithm the next section of the notebook provides some practical examples of each of the three algorithms.

* For the LinearRegression() algorithm the diabetes dataset and the Boston Housing dataset are used for demonstration.
* For the RandomForestClassifier() algorithm the Iris dataset along with a dataset obtained from my workplace are used for demonstration.
* For the KNeighborsClassifier() algorithm the breast-cancer-wisconsin dataset was used for demonstration.

<br/>

# 2) scipy.stats Jupyter Notebook

## Notebook objectives

* Provide a clear and concise overview of the scipy.stats Python library
* Provide an example hypothesis test using ANOVA. You should find a data set on which it is appropriate to use ANOVA, ensure the assumptions underlying ANOVA are met, and then perform and display the results of your ANOVA using scipy.stats.
* Appropriate plots and other visualisations to enhance your notebook for viewers.

To start with, the notebook provides an overview of the scipy.stats Python library, what it is, where it came from and where it is used. It's also shown that scipy.stats is just one part of the scipy Python library but is the part of interest for this notebook. The following includes some of the scipy.stats functionality that was used in this notebook;

* `stats.shapiro - checking for normal distribution`
* `stats.probplot - checking for normal distribution`
* `stats.levene - checking for homogenity of variances`
* `stats.ttest_ind - completing 2 sample t-test`
* `stats.f_oneway - completing the ANOVA testing`
* `Statsmodels.stats - completing the tukey post hoc test`

It's important to get some background statistical information before getting to hypothesis testing using ANOVA and that's what's provided in the next section of this notebook. This information will be useful as this progress and includes details on the null and alternative hypotheses, how hypothesis testing is complete, statistical significance, level of coinfidence and level of significance. There are some worked examples demonstrating the workings of the aformentioned detail included in this section.

With some background statistical information provided the next section looks at two sample t-testing. In this section an overview and demonstration of two sample t-testing is provided. In the demonstration, a taxi company wants to reduce costs and needs to know if the maintenance costs are higher for petrol or diesel cars. In the example, the null and alternative hypothesis are stated along with boxplots, normal probability plots, a 2 variances test and finally a 2 sample t-test.

Having looked at the two sample t-test, it's time to get to the main event, that being the ANOVA. ANOVA is detailed in the next section. The section starts with an overview of ANOVA, concepts such as the F-statistic and the p-value are explained. An important part of ANOVA is the assumptions and these are covered in the next section. In this notebook there are 6 assumptions included and discussed.

With the background on ANOVA complete the next section completes and ANOVA on a theoretical data set which consists of 4 moulding machines and 4 sets of tensile data results (one set of data per machine). The example checks the assumptions before completing the ANOVA, boxplots, distribution plots and probability plots are used to aid the explanation as the notebook works through the assumptions.

With all assumptions passed the ANOVA is complete, the results show that at least one of mean tensile strengths of the 4 machines is different from the others. Some post hoc (“after this” in Latin) tests are then used to uncover specific differences between the 4 sets of data.

A second ANOVA is then complete using data obtained from my workplace. It's good to use familar data when learning a new concept as the process/data is familar and relatable. In this example 4 machines are considered as the independent variable and bodylength the dependent variable. Once again the 6 assumptions are pre-requisite to completing the ANOVA. In this example there's a problem with assumption 6 "homogeneity of variances".

For the homogeneity of variances test the levene test was used. The p-value if 1.188e-05 is less than the significance level which was 0.05. The result here is that we must reject the null hypothesis that the variability from the towers is equal. There is enough evidence to conclude that the variability in the towers is different. For learning purposes it was decided to continue with the ANOVA but using 3 machines instead of 4 and dropping "Tower 4". Using the 3 machines the ANOVA is complete and followed up with some post hoc testing by way of a Tukey test.

## Contact

Keith Quinn @ [G00387815@gmit.ie](mailto:G00387815@gmit.ie)