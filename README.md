# Term-Deposit-Marketing-Project
# Background:

We are a small startup focusing mainly on providing machine learning solutions in the European banking market. We work on a variety of problems including fraud detection, sentiment classification and customer intention prediction and classification.

We are interested in developing a robust machine learning system that leverages information coming from call center data.

Ultimately, we are looking for ways to improve the success rate for calls made to customers for any product that our clients offer. Towards this goal we are working on designing an ever evolving machine learning product that offers high success outcomes while offering interpretability for our clients to make informed decisions.

# Data Description:

The data comes from direct marketing efforts of a European banking institution. The marketing campaign involves making a phone call to a customer, often multiple times to ensure a product subscription, in this case a term deposit. Term deposits are usually short-term deposits with maturities ranging from one month to a few years. The customer must understand when buying a term deposit that they can withdraw their funds only after the term ends. All customer information that might reveal personal information is removed due to privacy concerns.

# Methodology:
1- EDA for cleaning and exploring the data
2- Feature engineering: encoding cat variables, binning months into seeasons to reduce nomber of features, correlaiton matrix to delete highly corelated features
3- exploring the binary target: the data suffers from a highly imbalanced target
4- resampling the imbalanced target
5- applying Decision Tree, Random Forest, Logistic regression, XGBoost models
6- Assessing and avaluating the accuracy, F1 score, confusion matrix, precision-recall curve, ...
7- SHAP graphs for global model agnostic explenaiton

# Conclusion:

** Attained an impressive model prediction accuracy rate of 93%, reflecting the high precision and effectiveness of our machine learning algorithm.
** Duration of the telephone calls is the most importatnt parameter for convincieng customers to subscribe for the service. In other words, it really depends on how much time the operators talk to customers to convience them to use the service!¶

![SHAP_2](https://github.com/Alimale/Term-Deposit-Marketing-Project/assets/23621204/721a24e0-c7f0-4974-971c-8a0962bdeaf0)


​
![SHAP-1](https://github.com/Alimale/Term-Deposit-Marketing-Project/assets/23621204/5b9fcc2e-ae72-47c2-8827-a28c00f040be)
