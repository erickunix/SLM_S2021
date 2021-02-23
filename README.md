# SLM_S2021
Repository for Statistical Learning Methods - Summer semester 2020/21

**Required software**

During the course we'll use RStudio and Jupyter Notebook. 
To run the code provided during classes you'll need:
* R - https://cran.r-project.org/mirrors.html
* Python - https://www.python.org/downloads/ (for Windows user it's easy to install Python through Anaconda - https://anaconda.org/)
* RStudio - https://rstudio.com/products/rstudio/download/
* Jupyter Notebook or Jupyter Lab - https://jupyter.org/install 

Additionally you can install:
* Git - https://git-scm.com/
* PowerShell (for Windows) - https://github.com/PowerShell/PowerShell

**Modeling problem report**

Use the following dataset hosted on UCI repository: https://archive.ics.uci.edu/ml/datasets/Bank+Marketing (use `bank-additional-full.csv` file). It contains information related with direct marketing campaigns. All files and description are available under the given URL.

The task is to produce a report with following structure:

`5pts` 1) Introduction, problem/task description (you should choose at least one supervised learning task, provide description of target variable, rationale behind picking particular task and target), features explanation, dataset description

`10pts` 2) Cleaning and preprocessing data - removing or imputing missing data, standarization, one-hot encoding, handling outliers, feature extraction, merging categories etc. (some of these points may go to part 3 if EDA/exploration was the cause of particular action)

`10pts` 3) EDA (both graphical e.g. barplots, scatterplots and descriptive e.g. tables with statistics) with focus on exploring relations between features and target variable; include correlation matrix/heatmap between numerical variables; use one of the clustering (e.g. k-means, hierarchical clustering) or dimensionality reduction technique (e.g. PCA, t-SNE, UMAP) to derive additional insight from data

`10pts` 4) Create models (at least 3 distinct types of models) and tune hyperparameters for each model

`10pts` 5) Graphical (e.g. barplots of errors, ROC curves, residual graphs, etc.) and descriptive model assessment (comparing measures picked as performance criteria); remember to choose appropriate measure for the task - RMSE is measure for regression, not classification

`5pts` 6) Summary, short discussion on encountered problems, actions undertaken to solve them, possible shortcomings of used model/approach/data

Code and descriptions/comments should be in Jupyter or R Markdown notebook. Please send reports to _lukasz.krainski123@gmail.com_ or _lkrain@sgh.waw.pl_ with following naming convention <index_number>_SLM_S2021_Report.< extension > before **08.06.2021r. EOD**. 
  
Each email should have 2 attachments: 
- for Jupyter: `.ipynb` file and `.html/.pdf` file generated from notebook, 
- for R Markdown:  `.Rmd` file and `.html/.pdf` file generated from the script.

---
**Contact**

Name: Łukasz Kraiński

Email: lkrain@sgh.waw.pl or lukasz.krainski123@gmail.com

You can contact me through MS Teams and schedule consultation if needed. You can create an issue in the repository if you have remarks regarding repository content/structure.

---
**Lecturers**

* lecturer: Bogumił Kamiński
* laboratories: 
  * Groups 1 and 2 – Łukasz Kraiński
  * Group 3 – Michał Kot

---
**Schedule**

* lectures: Tuesdays, 8:00-10:35

* laboratories: every second Tuesday (check USOS schedule for your group for details)

---
**Lectures**

|Date |Subject|
|-----|-------|
| 2021-02-23 | Introduction to statistical learning|
| 2021-03-02 | Working with Git and GitHub|
| 2021-03-09 | Introduction to building prediction models|
| 2021-03-16 | Methods of evaluation of classifiers|
| 2021-03-23 | Regularization methods|
| 2021-03-30 | Local models|
| 2021-04-13 | Modeling causality|
| 2021-04-20 | Introduction to deep learning|
| 2021-04-27 | Machine learning use case (in cooperation with McKinsey)|
| 2021-05-04 | AutoML|
| 2021-05-11 | Introduction to the Julia language for data science|
| 2021-05-18 | Working with data in the Julia language|
| 2021-05-25 | Parallelizing computations with the Julia language|
| 2021-06-01 | Introduction to graph mining|
| 2021-06-08 | Explainable machine learning|

---
**Laboratories**
|# |Subject|
|--|-------|
|1 |Refresher on R and Python programming|
|2 |Methods of evaluation of classifiers|
|3 |Nonparametric regression models: smoothing spline, LOESS, GAM|
|4 |Classical machine learning models: CART, random forest|
|5 |Bayesian networks and probabilistic programming|
|6 |Deep Learning example + Dockerization|
|7 |Modeling competition|
|8 |Computer exam| 

---
**Literature**

Materials distributed on MS Teams

Mykel J. Kochenderfer, Tim A. Wheeler, And Kyle H. Wray (2022), Algorithms for Decision Making (https://algorithmsbook.com/)

Stephen Boyd and Lieven Vandenberghe, Introduction to Applied Linear Algebra
(http://vmls-book.stanford.edu/)

Gareth J., Witten D., Hastie T., Tibshirani R. (2013), An Introduction to Statistical Learning
with Applications in R (http://www-bcf.usc.edu/~gareth/ISL/)

Hastie T., Tibshirani R., Friedman J. (2013), The Elements of Statistical Learning
(http://www-stat.stanford.edu/~tibs/ElemStatLearn/)

Kamiński B., Zawisza M. (2012), Receptury w R. Podręcznik dla ekonomisty, Oficyna
Wydawnicza SGH (http://bogumilkaminski.pl/projekty/)

B. Kamiński, P. Szufel: Julia 1.0 Programming Cookbook, Packt Publishing, 2018
(https://www.packtpub.com/application-development/julia-10-programming-cookbook)

---
**Course evaluation criteria**

* Modeling problem report (50 points); deadline until last laboratory, subject of modelling will be discussed during first class; for more details see section _Modeling problem report_ above

* Laboratory examination (50 points); during last laboratory performed on-line; it will include both practical (writing R code) and theoretical questions (related to statistical models and machine learning)

* Possible extra points: 
  * homeworks
  * competition (7th class)
  * course: https://juliaacademy.com/p/introduction-to-dataframes-jl1 (5 points) - send an e-mail with certificate of completion before **08.06.2021r EOD**

---
**Grading rules**
|From |To|Final grade|
|-----|--|--------|
|0 |49| 2.0|
|50 |59 |3.0|
|60 |69 |3.5|
|70 |79 |4.0|
|80 |89 |4.5|
|90 |100 |5.0|
