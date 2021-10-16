# CIND820_FINAL-PROJECT
Final Project of CIND 820
Predictive Analytics of Bank Customers Credit: A Case Study of Germany
 
Literature Review, Data Description, and Approach
Professor: Dr Derya Kici
Student: Mohsen Selseleh
Student Number: 500726502
Date of Submission: Oct 18, 2021
 
Table of Contents
Abstract	3
Literature Review 	4
Sample Chart	8
Sample Table	9
 
Abstract

Bank credit means amount of money that a person could borrow from a bank or other financial institution. The bank decide on basis borrower’s credit rating, income, assets, debts,etc. . This process for banks always has risk of failure, when borrower neglects to pay the money obtained. Therefore, credit scoring is a challenging management issue. Nowadays, banks use the data mining techniques to build trained model by learning samples and trained model is used to make decision in new situations.
In this study, many factors determine credit of a customer as status of checking account, credit history, credit amount, saving account, employment, debts, age, ownership a house, number of people provide maintenance, etc. The dataset has historical data for 1000 customers of bank in Germany. The task prediction the credit of customer. The study is a typical classification problem which determine a customer is good or bad for a loan. The research will use a supervised learning (Neural Network, Decision Tree, Logistic Regression Analysis and Naïve Bayes) and ensemble algorithms (Gradient Boosting).


Literature Review

What do you already know about the topic?
The financial institutes need to know about credit of their customers. This kind of loan has labeled as customer credits which means customer’s ability to repay his/her loan. The credit allows the customers to buy goods and services without need to pay for them, immediately. The most evident example of customer credit is credit cards.
Bank credit means amount of money that a person could borrow from a bank or other financial institutes. This credit has a profitability risk, especially sometimes customers could not afford to repay their debts. Because the fund is limited, the banks as the most important financial institutes, must assigned their funds carefully to gain more profit. Prediction credit customer is so critical for preventing risk in the banking sector. Because failing to repay has disadvantages for bank and customer, too. The customer should pay additional interest charges if they could not repay on time.

The credit risk is one the most important hazards that threat banks and they try to with risk management knowledge and validation models study this risk and change its threat to opportunity. 
The main part of study of credit risk is finding good and bad customers which is a imperative task for banks. Nowadays, Machine Learning Algorithms make a great improvement at these kinds of studies because dataset is big data.
What do you have to say critically about what is already known?
The researchers used different kind of classification models as Neural Network model, Logistic Regression model, Decision Tree, … But it could see that Neural Network model is used more than others which is time consuming method and choosing its potential input variable is so critical. 
Has anyone else ever done anything the same?
No, this research is a new one on basis of method and dataset. This research considers a collection of classification methods and a new recently method, XGBoost which is from ensemble learning paradigm. 
Has anyone else done anything that is related?
Lee et al (2006) studied credit customer risks with Classification and regression trees.
Chen et al (2007) studied customer credit with Support Vector Machine method
Kumar et al (2008) predict customer credit churn in banks using data mining
Li et al (2010) predict customer credit card segmentation based on data mining.
Afsar et al (2014) studied Customer credit clustering for granting facilities.
Where does your work fit in with what has gone before?
It uses a collections of the past studies.
Why is your research worth doing in the light of what has already been done?
This research will use classification methods (as Neural Network, Logistic Regression, Decision Tree and Naïve Bayes) as previous studies, but it will add new method XGBoost and will try to show comparison of their performance. 
 On the other hand, their datasets did not consider a complete feature as dataset used for this research.


The Goal of research
Our goal is prediction customer credit and comparison performance Neural Network, Logistic Regression and Decision Tree, Naïve Bayes and XGBoost algorithms in a German Bank in 1994.
Questions of the study
Is there any significant correlation between independent variables?
Which variables have the significant relation with dependent variable (credit customer)?
Which variables have stronger relation with dependent variable (credit customer)?
Which model has a better performance at prediction of credit customer?
Method
Neural networks make a model between inputs and outputs and to show the patterns in the dataset. Training neural network is the most important part of it.
Logistic Regression is a type of generalized linear models, it is a function of independent variables for the prediction the probability of a binary (nominal or ordinal) variable that the probability value changes between 0 and 1.
Decision Tree is a method that finds knowledge in big dataset. Decision Tree is one of the most used techniques in classification and prediction. The disadvantage is that a little change in the sample may cause big difference in classifying it.
Naïve Bayes is a classification method based on Bayes’ theorem. It assumes that the features are independent.
As Burkov (2019) stated that gradient boosting is one the most powerful ensemble machine learning algorithms which could manage big dataset, easily and quickly. Also, it creates very accurate models. The important hyperparameters of it are the number of trees and the depth of trees. Majority of machine learning algorithms have their limitations,but ensemble learning approach could boost the performance prediction. Two principal ensemble learning methods are boosting and bagging.
A brief descriptive statistics of the selected dataset
Dataset has 21 features for one thousand instances. seven variables are interval and thirteen are nominal. The dependent variable is Cost Matrix that show customer was good (1) or bad (0) in regard with repay their loan.

Sample Chart
 
Sample Table
Variable	mean	std	
min	max


Duration in month	20.903	12.058	4.0	72.0
Credit amount	3271.258	2822.736	250.0	18424.0
Installment rate in percentage of disposable income	2.973	1.118	1.0	4.0
Present residence since	2.845	1.103
	1.0	4.0
Age in years	35.546	11.375	19.0	75.0
Number of existing credits at this bank	1.407	0.577
	1.0

	4.0

Number of people being liable to provide maintenance for	1.155	0.362	1.0	2.0

Reference
Afsar, Amir, R. Houshdar Mahjoub, and B. Minaie Bidgoli (2014). Customer credit clustering for presenting appropriate facilities. Management Researches in Iran 17(4),1-24, https://www.sid.ir/en/journal/ViewPaper.aspx?ID=491564
Burkov,A.(2019). The hundred-page machine learning book. Andriy Burkov
Chen, W., Ma, C., & Ma, L. (2009). Mining the customer credit using hybrid support vector machine technique. Expert systems with applications, 36(4), 7611-7616,https://doi.org/10.1016/j.eswa.2008.09.054
Kumar, A., Ravi, V. (2008). Predicting credit card customer churn in banks using data mining. International Journal of Data Analysis Techniques and Strategies, 1(1), 4-28, DOI:10.1504/IJDATS.2008.020020
Lee, T. S., Chiu, C. C., Chou, Y. C., & Lu, C. J. (2006). Mining the customer credit using classification and regression tree and multivariate adaptive regression splines. Computational Statistics & Data Analysis, 50(4), 1113-1130,
 https://doi.org/10.1016/j.csda.2004.11.006



Appendix
A link to a repository on GitHub
https://github.com/Mohsenselseleh/CIND820_FINAL-PROJECT/blob/main/German_Credit_Final%20Project.ipynb
Dataset 
Statlog (German Credit Data) Data Set
https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)

 


