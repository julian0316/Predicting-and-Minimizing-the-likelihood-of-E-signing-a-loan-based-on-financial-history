# Predicting the likelihood of E-signing a loan based on financial history

# Overview:

Lending companies work by analyzing the financial history of their loan applicants, and choosing whether the applicant is too risky to be given a loan. If the applicant is not, the company then determines the terms of the loan. To acquire these applicants, companies can organically receive them through their websites/apps, often with the help of advertisement campaigns. Other times, lending companies partner with peer-to-peer (P2P) lending marketplaces, in order to get leads of possible applicants. Some example marketplaces include Upstart, lending tree, and lending club. 

In this project, we are going to assess the quality of the leads our company receives from these marketplaces. 

# Market:
The target audience is the set of loan applications who reached out through an intermediary marketplace.

# Product: 
A Loan

# Goal: 
Develop a model to predict for quality applicants. In this case study, “quality” applicants are those who reach a key part of the loan application process.

# Business Challenge:

This case is a fintech company that specializes on loans. It offers low APR loans to applicants based on their financial habits, as almost all lending companies do. This company has partnered with a P2P lending marketplace that provides real-time leads (loan applications). The numbers of conversions from these leads are satisfactory.

We are creating a model that predicts whether or not these leads will complete the electronic signature phase of the loan application (a.k.a e -signed). The company seeks to leverage this model to identify who the less quality applicants are (e.g. those who are nor responding to the onboarding process), and experiment with giving them different onboarding screens. The reason for selecting e-signing process as the response variable is due to the structure of the loan application.

The official application begins with the lead arriving into our website after we opted to acquire it. Here, the applicant begins the onboarding process to apply for the loan. The user starts to provide more financial information by going over every screen of the onboarding process. This first phase ends with the applicant providing his/her signature indicating all of the given information is correct.

Any of the following screens, in which the applicant is approved/denied and given the terms of the loan, is dependent on the company, not the applicant. Therefore, the effectiveness of the onboarding is measured up to the moment the applicant stops having control of the application process. 

# Data:

We have access to the applicant’s financial data (which they have entered in the marketplace) before they start the onboarding process. This data includes personal information like age, and time employed, as well as other financial metrics. Our company utilizes these financial data points to create risk scores based on many different risk factors.

In this case study, we are given the set of scores from algorithms built by the finance and engineering teams. Furthermore, the marketplace itself provides us with their own lead quality scores. We will leverage both sets of scores, as well as small list of personal/financial features to predict if the user is likely to respond to our current onboarding process.


