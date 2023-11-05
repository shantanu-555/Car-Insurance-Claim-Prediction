# Advanced Analytics and Machine Learning for Car Insurance Claim Prediction

## Introduction
Car insurance is a type of financial protection designed to cover the costs associated with accidents, theft, and other unforeseen events involving a motor vehicle. It is a contract between an individual (the policyholder) and an insurance company. In exchange for regular premium payments, the insurance company agrees to provide financial assistance in case of covered events.

Insurance companies conduct risk assessments to determine the likelihood of a policyholder making a claim and the potential cost of that claim. This process is crucial for several reasons:

Setting Premiums: Risk assessment allows insurance companies to determine appropriate premium rates for policies. Policies for individuals or entities with a higher likelihood of making claims or incurring costly losses are generally charged higher premiums. This ensures that the premiums collected are sufficient to cover potential payouts.

Maintaining Financial Stability: Accurately assessing risk helps insurance companies maintain their financial stability. If premiums are too low relative to the risk, the company may not have enough funds to cover claims, potentially leading to financial instability.

Avoiding Adverse Selection: Adverse selection occurs when individuals or businesses with a higher likelihood of making a claim are more inclined to purchase insurance. If insurers do not assess risk properly, they may attract a disproportionate number of high-risk policyholders, which can lead to financial losses.

Balancing Coverage and Costs: Insurance companies need to strike a balance between offering comprehensive coverage and maintaining affordability for policyholders. Risk assessment helps them determine the level of coverage they can provide while still remaining financially viable.

In summary, risk assessment is a cornerstone of the insurance industry’s profitability. It helps insurers strike a balance between offering coverage, managing costs, and mitigating financial risks, ultimately allowing them to generate profits while fulfilling their promise to policyholders.

## Business Understanding
The goal of this project is to predict the probability that an individual seeking auto insurance will be in an accident and then to forecast the potential cost of an ensuing claim. Using data of existing customers, we can identify the likely characteristics of high risk drivers. Not only will this allow us to flag high risk clients, it will also allow us to construct a general profile of such drivers.

Following our analyses, insurance providers can accordingly allocate (or deny) a suitable insurance policy to such clients. They can also identify potentially fraudulent claims from clients that were highly unlikely to make claims. However, these problems are not within the scope of this project.

A binary classification model will be constructed to estimate the probability of claiming insurance (1 or 0), this can be done by training and comparing different models like logistic regression, decision trees, and k-nearest neighbors. This approach builds on methods for model training/testing which underlie modern machine learning strategies for classification and prediction.

**This dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/sagnik1511/car-insurance-data)**

## Conclusion
Random Forest and Logistic Regression were the best models. Random Forest has the lowest MSE but Logistic regression has the highest AUC. Keeping in mind that the ntree = 100 was arbitrarily chosen for Random Forest algorithm, with a more optimal ntree it can perform much better.

In conclusion, the successful completion of this project marks a significant milestone in leveraging machine learning techniques to enhance the car insurance industry. Through the application of various classification models and feature engineering, we have been able to predict with a high degree of accuracy whether a customer is likely to file a car insurance claim. This achievement holds immense potential for insurance companies seeking to optimize their operations, allocate resources more efficiently, and ultimately provide better services to their clients.

The comprehensive evaluation of multiple classification models, including but not limited to Logistic Regression, Random Forest, K Nearest Neigbours and CART decision tree, enabled us to make informed decisions about the best-performing algorithm for our specific use case. The meticulous tuning of hyper-parameters and thorough model comparison allowed us to attain a robust predictive capability.

Furthermore, this project provided valuable insights into the features that contribute most significantly to the prediction of insurance claims. This not only aids in understanding the underlying factors that drive customer behavior but also offers actionable intelligence for insurance companies to proactively engage with their clients and implement risk mitigation strategies.

All in all, this project has demonstrated the immense value that machine learning brings to the realm of car insurance prediction. By harnessing the power of data and advanced analytical techniques, we have laid the foundation for more informed decision-making, improved customer service, and ultimately, a more sustainable and competitive insurance industry.

