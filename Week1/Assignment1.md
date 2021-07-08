Part 1:
1. In the notes of Week 1, we compared & contrasted MLOps with DevOps. In this question, you need to understand what is meant by the term ***AIOps***, & then contrast it with MLOps.

Answer: 

       1. AIOps means using Artificial Intelligence for optimization, simplification, acceleration and mainly, automation of IT Operations. Whereas MLOps helps us build, scale and deploy machine learning algorithms to production reliably and efficiently. 
       
       
       2. AIOps utilizes big data, advanced analytics, and machine learning techniques for achieving the above goal. Whereas MLOps utilizes the concepts of ML, DevOps & Data Engineering for providing the above mentioned utility. 
       
       3. MLOps provides tools and techniques for efficient deployment of models to production, whereas AIOps is more about which of these tools are automated in order to simplify the process. 
       
       4. MLOps facilitates collaboration between different teams, whereas AIOps helps them improve their IT infrastructure.


References: https://www.ibm.com/in-en/cloud/learn/aiops , https://opensource.com/article/21/2/aiops-vs-mlops , notes

2. Interpretable Machine Learning is another concept that has attracted lot of attention recently & is promoted by most of the MLOps frameworks. Explain what it means for a linear regression model to be interpretable.

Answer:

       A linear regression model provides a prediction for the target variable as a weighted sum of inputs. Interpretability of a model means that apart from giving the accurate prediction, it should be able to explain how and why it came to that prediction. The linearity of a linear regression model helps it to be interpretable and provide simplistic explanations. The weights signify the contribution and dependence of each feature to the prediction. For an instance, if we add one to the feature (numerical)value, the prediction will increase by the weight of that feature. Effect plots can be a good way to visualise those effects. Another parameter for it's interpretability is R-squared measurement(how much of total variance of target outcome is explained by the model). Models with R-squared value close to 1 are considered good. Furthermore, we can also analyse the importance of a certain feature by the t-statistic(estimated weight scaled with its standard error).. A way to build more interpretable linear regression models is increasing the selectivity by using L1 regression i.e., training sparse linear models. In a nutshell,   a linear model is interpretable as long as the relationship between features and target values is linear and the features are independent of each other.
       
References: https://christophm.github.io/interpretable-ml-book/limo.html , https://towardsdatascience.com/interpretable-machine-learning-models-aef0c7be3fd9 


Part 2:
![image](https://user-images.githubusercontent.com/64677521/124766697-c4fb9100-df54-11eb-9460-f3444a24474a.png)

