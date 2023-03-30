# Profitable Loan Investment Modeling Case Study

<!--
*** Thanks for checking out this project. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
-->


<!-- ABOUT -->
## Topic
The purpose of this project was to use historical data from online peer-to-peer lending platforms such as Prosper and LendingClub to analyze the risk and return associated with investments in these platforms. The project used data from loans issued between 2008 and 2019, containing features such as loan amount, interest rate, monthly installment amount, loan status, and several additional attributes related to the borrower. 

Through the analysis of the data, the project aimed to construct informed investment strategies by predicting which loans are more or less likely to default and which will yield higher or lower returns.


## Overview

We employed feature engineering on continuous features to ensure all columns are of the same type and our outcome column was based on ‘loan_status’. We fit various classification models such as Naive Bayes, l1 regularized logistic regression, l2 regularized logistic regression, decision tree, random forest classifier, and a multi-layer perceptron. 

We tuned hyperparameters for each model to optimize performance. We also tested the hypothesis that if you wanted to increase the number of loans you wished to invest in, you would eventually “run out” of good loans to invest in. We found that as we add more bonds to our portfolio, our total return decreases. We identified two pain points in this market that could hinder returns: 1. single issuer and market maker - supply shortage and 2. limited product offerings.


## Goal

This project employed predictive analytics to predict the likelihood of loan default and used predictive models to develop various investment strategies. We set up our model training and evaluation by importing necessary packages and loading the data from our pickle file. We tuned hyperparameters for each model, such as “var_smoothing” for Naive Bayes and “C” for logistic regression, and used cross-validation to determine the best-performing model. 

We also looked at the trend of return versus our portfolio size and found that as we choose the best loans and add more bonds to our portfolio, our total return decreases. We also identified various pain points that could compound our portfolio size problem, such as single issuer and market maker - supply shortage and limited product offerings.


## Code

#### [Phase 3 Code](https://github.com/sr9dc/Loan_Investments_Case_Study/blob/main/Case_Study%2C_Phase_3_mkasari_srajulad_kellymcm_nthomas_FINAL.ipynb)



## Results

View the report pdf to see our detailed modeling approaches. 


#### [Phase 3 Report](https://github.com/sr9dc/Loan_Investments_Case_Study/blob/main/Case_Study_Phase_3_Writeup_mkasari_srajulad_kellymcm_nthomas.pdf)


## Team Members

Mira Kasari, mkasari

Sairathan Rajuladevi, srajulad

Kelly McManus, kellymcm

Cole Thomas, nhthomas

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.


<!-- CONTACT -->
## Contact

Sai Rajuladevi: https://www.linkedin.com/in/sai-rajuladevi/






