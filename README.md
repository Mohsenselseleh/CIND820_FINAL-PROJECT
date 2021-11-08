Predictive Analytics of Bank Customers Credit: A Case Study of Germany
 
Literature Review, Data Description, and Approach
Professor: Dr Derya Kici
Student: Mohsen Selseleh
Student Number: 500726502
Date of Submission: Nov 7, 2021
 
Table of Contents
Abstract …………………………………………………………………………….3
Literature Review…………………………………………………………………………………………5
Sample Chart	12
Chart …………………………………………………...………………...………..16
Reference………………………………….……………………...……….………17
Appendix………………………..…………………………….…………………..19

 
 
Abstract

Bank credit means amount of money that a person could borrow from a bank or other financial institution. The bank decides on basis borrower’s credit rating, income, assets, debts, etc. This process for banks always has risk of failure, when borrower neglects to pay the money obtained. Therefore, credit scoring is a challenging management issue. Nowadays, banks use the data mining techniques to build trained model by learning samples and trained model is used to make decision in new situations.In this study, many factors determine credit of a customer as status of checking account, credit history, credit amount, saving account, employment, debts, age, ownership a house, number of people provide maintenance, etc. This study is a typical classification problem which determine a customer is good or bad for a loan. The research will use a supervised learning (Neural Network, Decision Tree, Logistic Regression Analysis, KNN, and Naïve Bayes) and ensemble algorithms (Gradient Boosting , Random Forest). The dataset has historical data for 1000 customers of bank in Germany.
I will try to find answers for these questions.
 
Which quantitative variables have stronger significant relation with dependent variable (credit customer)?
Which model has a better performance at prediction of credit customer?
And I will try to test my hypothesis:
Customers who have bad credit are different in qualitative variables with customers who have good credit.









Module 2

Introduction
Customer credit is an ever-growing threat in the finance sector. The financial institutes need to know about credit of their customers. This kind of loan has labeled as customer credits which means customer’s ability to repay his/her loan. The credit allows the customers to buy goods and services without need to pay for them, immediately. The most evident example of customer credit is credit cards. Bank credit means amount of money that a person could borrow from a bank or other financial institutes. This credit has a profitability risk, especially sometimes customers could not afford to repay their debts. Because the fund is limited, the banks as the most important financial institutes, must assigned their funds carefully to gain more profit.
The main part of the study of credit risk is finding good and bad customers which is a imperative task for the banks. Nowadays, Machine Learning Algorithms make a great improvement at these kinds of studies because dataset is big data. The Customer card dataset is highly imbalanced because there will be more good customer credit when compared to bad customer credit.
Detection credit customer is so critical for preventing risk in the banking sector. Because failing to repay has disadvantages for bank and customer, too. The customer should pay additional interest charges if they could not repay on time. The credit risk is one the most important hazards that threat banks and they try to with risk management knowledge and validation models study this risk and change its threat to opportunity. 
As transactions become the frequent mode of payment, customer credit becomes more important, Finding the bad customer credit using traditional methods is time consuming and incorrect. Nowadays, financial institutes use machine learning techniques to study customer credit problem.
The study Customer credit is highly related to sampling approach, selection of variables and machine learning methods used. This study uses under-sampling method with naïve bayes, k-nearest neighbor, neural network, decision trees, random forest, logistic regression, and Gradient Boosting on highly imbalanced customer credit dataset.
Dataset
The dataset of customer credit is from a German bank containing 1000 items. The dataset will be balanced with under-sampling technique. The dataset sourced from UCI Machine Learning Repository; its link is found at appendix. This dataset classifies people described by a set of attributes as good or bad credit risks by a German bank in 1994, it consists of 1000 customers. The data set is highly imbalanced and skewed. We have 21 attributes; twenty attributes are independent variable, and we have one dependent variable (cost matrix). Attributes of Customer Credit of a German bank dataset is found at Appendix.
Previous research
A comparison of logistic regression and naïve bayes is done by Ng et al (2002). Their results show that if the number of training examples is increased, naive Bayes perform better, but discriminative logistic regression generally overtakes the performance of naive Bayes. Maes et al (2002) have studied decision tree, neural networks, and logistic regression, they show that bayesian network is better than neural network in finding credit card fraud. Bhattacharvva et al (2011) have evaluated support vector machines and random forests with logistic regression and neural networks, they show that logistic regression performs better than SVM. Alborzi et al (2016) studies credit customers with Artificial Neural Networks and they show that NN has good accuracy in prediction customer credit. Lee et al (2006) studied credit customer risks classification and regression tree (CART) and multivariate adaptive regression splines (MARS). Their results demonstrate that CART and MARS both have better average correct classification rate in comparison with discriminant analysis, logistic regression, neural networks, and support vector machine (SVM). Chen et al (2007) studied customer credit with Support Vector Machine method and it has great accuracy. Anil et al (2008) predict customer credit churn in banks using ensemble learning and oversampling techniques with a good acuracy. Li et al (2010) predict customer credit card segmentation, they used Logistic Regression, decision trees, Random Forest, Radial Basis Function, network, and Support Vector Machine (SVM). their results show that the tenfold cross-validation method on the Synthetic Minority Oversampling Technique (SMOTE) data has produced excellent results. Shen et al (2007) study decision tree, neural networks, and logistic regression, they show that neural networks and logistic regression perform better than decision trees. Sahin et al (2011) study decision tree and svm approaches and they show that SVM is better than decision tree, their result show that ANN work better than LR classifiers. Sherly et al (2012) study decision tree, neural network and naïve bayes classifiers. They show that neural networks are suitable for big data sets, and it is time consuming but naïve bayes is more accurate and faster. Patil et al (2013) use a meta-classification method which consists of tree, naïve Bayesian and k-nearest neighbor algorithms, results show performance improves. Afsar et al (2014) studied Customer credit clustering K-means for granting facilities with ten clusters. Fahmi et al (2016) compare naïve bayes, k-nearest neighbor and logistic regression techniques on accuracy, sensitivity, specificity and MCC metrics. The researchers show that LR has better performance. They argue that it could see that Neural Network model is used more than others which is time consuming method and choosing its potential input variable is so critical
The Goal of research
The main goal of study of credit risk is finding good and bad customers, it is so imperative task for banks. Nowadays, Machine Learning Algorithms make a great improvement at these kinds of studies because dataset is big data and highly imbalanced. My goal is prediction customer credit and comparison performance Neural Network, Logistic Regression and Decision Tree, Naïve Bayes, KNN, Random Forest and XGBoost algorithms in a German Bank in 1994.
Method of Research
This research is a Supervised machine learning one which there are pre-defined set of “training examples”, it facilitates its ability to receive to an accurate conclusion for new data set.
Logistic Regression is a type of generalized linear models, it is a function of independent variables for the prediction the probability of a binary (nominal or ordinal) variable that the probability value changes between 0 and 1.
Decision Tree is a method that finds knowledge in big dataset. Decision Tree is one of the most used techniques in classification and prediction. The disadvantage is that a little change in the sample may cause big difference in classifying it.
Random Forest is an ensemble of decision trees, generally trained via the bagging method, it is more convenient and optimized for decision trees. The random forest searches for the best feature among a random subset of features (Geron,2019)
Naïve Bayes is a classification method based on Bayes’ theorem. It assumes that the features are independent. It chooses the decision based on the highest probability.
The k-nearest neighbor perform classification based on a similarity measure, like Euclidean, Manhatan(both of them for continuous variables) or Minkowski distance (categorical variables)functions(Geron,2019).
The logistic regression estimates the probability of a binary response based on one or more variables. It finds the best-fit parameters to a nonlinear function called sigmoid.
Burkov (2019) stated that gradient boosting is one the most powerful ensemble machine learning algorithms which could manage big dataset, easily and quickly. Also, it creates very accurate models. The important hyperparameters of it are the number of trees and the depth of trees. Majority of machine learning algorithms have their limitations, but ensemble learning approach could boost the performance prediction. Two principal ensemble learning methods are boosting and bagging.
Machine learning metrics
In my research, I use the following formulae to evaluate, accuracy and precision. The Mathews correlation coefficients (MCC) is a machine learning measure which is used to check the balance of the binary (two class) classifiers. It considers all the true and false values that is why it is generally regarded as a balanced measure can be used even if there are different classes.
 


A brief descriptive statistics of the selected dataset
Dataset has 21 features for one thousand instances. seven variables are quantitative and thirteen are nominal. The dependent variable is Cost Matrix that show customer was good (1) or bad (0) in regard with repay their loan.

Sample Chart
 
Sample Table for seven quantitative variables
Variable	mean	std	medain	
min	max


Duration in month	20.903	12.058	18.0
	4.0	72.0
Credit amount	3271.258	2822.736	2319.5
	250.0	18424.0
Installment rate in percentage of disposable income	2.973	1.118	3.0
	1.0	4.0
Present residence since	2.845	1.103
	3.0
	1.0	4.0
Age in years	35.546	11.375	33.0
	19.0	75.0
Number of existing credits at this bank	1.407	0.577
	1.0
	1.0

	4.0

Number of people being liable to provide maintenance for	1.155	0.362	1.0
	1.0	2.0

Thirteen nominal variables
Nominal Variables	mode
Status of existing checking account	A14

Credit history	A32

Purpose	A43

Savings account/bonds	A61

Present employment since	A73

Personal status and sex	A93

Other debtors / guarantors	A101

Property	A123

      Other installment plans	A143
Housing	A152

Job	A173

Telephone
	A191

foreign worker	










Graph methodology














Reference
Afsar, A., Houshdar M. R., &B. Minaie B. (2014). Customer credit clustering for presenting  
     appropriate facilities. Management Researches in Iran 17(4),1-24.
     https://www.sid.ir/en/journal/ViewPaper.aspx?ID=491564
Alborzi, M., & Khanbabaei, M. (2016). Using data mining and neural networks techniques to
     propose a new    hybrid customer behaviour analysis and credit scoring model in banking 
     services based on a developed RFM analysis method. International Journal of Business
     Information Systems, 23(1), 1-22.
Awoyemi, J. O. (2017). Credit card fraud detection using Machine Learning Techniques: A
    Comparative Analysis. A comparative analysis. In 2017 International Conference on 
    Computing Networking and Informatics (ICCNI) (pp. 1-9). IEEE.
Bhattacharyya, S., Jha, S., Tharakunnel, K., & Westland, J. C. (2011). Data mining for credit card
    fraud: A comparative study. Decision support systems, 50(3), 602-613.
Burkov,A.(2019). The hundred-page machine learning book. Andriy Burkov
Chen, W., Ma, C., & Ma, L. (2009). Mining the customer credit using hybrid support vector 
     machine technique. Expert systems with applications, 36(4), 7611-7616. 
     https://doi.org/10.1016/j.eswa.2008.09.054
Dornadula, V. N., & Geetha, S. (2019). Credit card fraud detection using machine 
     learning algorithms. Procedia computer science, 165, 631-641.
Fahmi, M., Hamdy, A., & Nagati, K. (2016). Data mining techniques for credit card fraud
     detection: Empirical  study. Sustainable Vital Technologies in Engineering & Informatics, 1-9.
Géron, A. (2019). Hands-on machine learning with Scikit-Learn, Keras, and TensorFlow:
     Concepts, tools, and techniques to build intelligent systems. O'Reilly Media.
Kumar, A.& Ravi, V. (2008). Predicting credit card customer churn in banks using 
     data mining. International Journal of Data Analysis Techniques and
     Strategies, 1(1), 4-28.DOI:10.1504/IJDATS.2008.020020
Lee, T. S., Chiu, C. C., Chou, Y. C., & Lu, C. J. (2006). Mining the customer credit 
    using classification and regression tree and multivariate adaptive regression
   splines. Computational Statistics & Data Analysis, 50(4), 1113-1130.
   https://doi.org/10.1016/j.csda.2004.11.006
Li, Z., Liu, G., & Jiang, C. (2020). Deep representation learning with full center loss for credit 
   card fraud  detection. IEEE Transactions on Computational Social Systems, 7(2), 569-579.
Maes, S., Tuyls, K., Vanschoenwinkel, B., & Manderick, B. (2002). Credit card fraud detection 
    using Bayesian and neural networks. In Proceedings of the 1st international naiso congress on 
    neuro fuzzy technologies, 261-270.
Ng, A. Y., & Jordan, M. I. (2002). On discriminative vs. generative classifiers: A comparison of 
    logistic regression and naive bayes. In Advances in neural information processing  
    systems     (pp.        841-848).
Patil, S., Nemade, V., & Soni, P. K. (2018). Predictive modelling for credit card fraud detection 
    using data analytics. Procedia computer science, 132, 385-395.
Sahin, Y., & Duman, E. (2011). Detecting credit card fraud by ANN and logistic regression.
     In 2011 International Symposium on Innovations in Intelligent Systems and Applications (pp. 
     315-319). IEEE.
Shen, A., Tong, R., & Deng, Y. (2007). Application of classification models on credit card
     fraud   detection. In 2007 International conference on service systems and service   
     management ,(pp.1-4). IEEE.
Sherly, K. K., & Nedunchezhian, R. (2010). BOAT adaptive credit card fraud detection system.
    In 2010 IEEE International Conference on Computational Intelligence and Computing
   Research (pp. 1-7). IEEE.

Appendix
A link to a repository on GitHub
https://github.com/Mohsenselseleh/CIND820_FINAL-PROJECT/blob/main/German_Credit_Final%20Project.ipynb
Dataset
Statlog (German Credit Data) Data Set
https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)
Attributes of Customer Credit of a German bank dataset
Attribute 1: (qualitative)
Status of existing checking account
A11 : ... < 0 DM
A12 : 0 <= ... < 200 DM
A13 : ... >= 200 DM / salary assignments for at least 1 year
A14 : no checking account

Attribute 2: (numerical)
Duration in month
Attribute 3: (qualitative,nominal)
Credit history
A30 : no credits taken/ all credits paid back duly
A31 : all credits at this bank paid back duly
A32 : existing credits paid back duly till now
A33 : delay in paying off in the past
A34 : critical account/ other credits existing (not at this bank)
Attribute 4: (qualitative,nominal)
Purpose
A40 : car (new)
A41 : car (used)
A42 : furniture/equipment
A43 : radio/television
A44 : domestic appliances
A45 : repairs
A46 : education
A47 : (vacation - does not exist?)
A48 : retraining
A49 : business
A410 : others
Attribute 5: (numerical)
Credit amount
Attibute 6: (qualitative, ordinal)
Savings account/bonds
A61 : ... < 100 DM
A62 : 100 <= ... < 500 DM
A63 : 500 <= ... < 1000 DM
A64 : .. >= 1000 DM
A65 : unknown/ no savings account
Attribute 7: (qualitative,ordinal)
Present employment since
A71 : unemployed
A72 : ... < 1 year
A73 : 1 <= ... < 4 years
A74 : 4 <= ... < 7 years
A75 : .. >= 7 years
Attribute 8: (numerical)
Installment rate in percentage of disposable income
Attribute 9: (qualitative,nominal)
Personal status and sex
A91 : male : divorced/separated
A92 : female : divorced/separated/married
A93 : male : single
A94 : male : married/widowed
A95 : female : single

Attribute 10: (qualitative,nominal)
Other debtors / guarantors
A101 : none
A102 : co-applicant
A103 : guarantor
Attribute 11: (numerical)
Present residence since
Attribute 12: (qualitative,nominal)
Property
A121 : real estate
A122 : if not A121 : building society savings agreement/ life insurance
A123 : if not A121/A122 : car or other, not in attribute 6
A124 : unknown / no property
Attribute 13: (numerical)
Age in years
Attribute 14: (qualitative,nominal)
Other installment plans
A141 : bank
A142 : stores
A143 : none
Attribute 15: (qualitative,nominal)
Housing
A151 : rent
A152 : own
A153 : for free
Attribute 16: (numerical)
Number of existing credits at this bank
Attribute 17: (qualitative,nominal)
Job
A171 : unemployed/ unskilled - non-resident
A172 : unskilled - resident
A173 : skilled employee / official
A174 : management/ self-employed/
highly qualified employee/ officer
Attribute 18: (numerical)
Number of people being liable to provide maintenance for
Attribute 19: (qualitative,nominal)
Telephone
A191 : none
A192 : yes, registered under the customers name
Attribute 20: (qualitative,nominal)
foreign worker
A201 : yes
A202 : no
Attribute 21:(qualitative,nominal)
1: good
2: bad



