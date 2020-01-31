## Problem Statement

Automobiles have progressed slowly over the last century. Most cars on the road today are still powered by gasoline, a non-renewable resource that pollutes the air and contributes to global warming. There is one manufacturer that is revolutionizing transportation with electric vehicles: Tesla Motors. We have decided to investigate subreddit titles from a popular American social news website, Reddit, to better understand the public sentiments surrounding Tesla. Our goal is to learn the text of subreddit titles and correctly classify them as originating from subreddit 'cars' or 'teslamotors'. We plan to solve this problem using Logistic Regression and Multinomial Naive Bayes Classifier. Our models will be evaluated using Accuracy Scores. As Data Scientists of the 21st century, it is important we identify what differentiates the public opinion of innovative brands and leverage this to influence the remaining population to transition to clean energy sources.
_____________________________________________________________________


### Alex's Data Dictionary ###

|Feature|Type|Dataset|Description|
|---|---|---|---|
|Title|object|-| |
|Self Text|object| |
|Subreddit|object| |
|Created UTC|integer| |
|Author|object| |
|Number of Comments|integer| |
|Score|integer| |
|Is Self|boolean| |
|Time Stamp|object?| |

## Conclusion and Evaluation

All of our models were more successful than the baseline in classifying the subreddit, but our Count Vectorized Logistic Model outperformed the rest with an accuracy score of 88.5%. We are successful in building a model that can reasonably classify a title of a reddit post to belonging to subreddit 'teslamotors' or 'cars'. We were also successfull in identifying key words beyond the make and model that hold significance, such as autopilot, v10, and summon. Tesla spends $0 on advertising, so it is not surprising if the population is not familiar with these features. If we can educate the public on new technologies that exist on Tesla vehicles, we can reduce the dependency on gas, slow down global warming and pollution, and save some lives with autopilot features.