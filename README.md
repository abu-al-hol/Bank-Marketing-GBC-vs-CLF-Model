# Bank-Marketing-GBC-vs-CLF-Model

In a quick search for a dataset that could be used to demonstrate my knowledge of Machine Learning (ML) models that we learned in class this year, I determined that the Bank Marketing Dataset (below) gave me the right amount of depth, size, and sophistication to evaluate at least two different ML algorithms. I decided to try the classic logistic regression (clf) and then compare it to gradient boosting (gbc). Both performed generally well, with the gbc model having a much better recall than the clf model. Given that the outcome, or target variable, was highly skewed, it was evident that there would be some issues making a fair model that generally performed well against all metrics. 

### Introduction - Bank Marketing Dataset  

**Source:**  
UCI Machine Learning Repository.  
[Bank Marketing Dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing)

This dataset contains information related to direct marketing campaigns conducted by a Portuguese banking institution.  
The campaigns were based on telephone calls, and in many cases multiple contacts with the same client were required to determine whether the client would subscribe to a bank term deposit (`"yes"`) or not (`"no"`). A well-written data dictionary can be reviewed at the source URL above.
