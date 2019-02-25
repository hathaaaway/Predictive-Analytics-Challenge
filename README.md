# Predictive-Analytics-Challenge
This project analyzed Brandzooka Advertising Performance Data to predict the performance of a specific advertisement. I Developed a machine-learning algorithm that can predict the effectiveness of an advertising. The model also generated the features highlights the features that predict advertising effectiveness.

### Model

In this project, I used **LassoLarsCV**, **LarsCV**, **RidgeCV**, **ElasticNetCV**, and **OrthogonalMatchingPursuitCV** to train my data, and RidgeCV with fixed alpha values turns out to be the best model. Since random_state will select a random feature to update, I stimulated the spilting process for 20000 times to find the best r2 in each model. RidgeCV was able to output optimal r2 for both training and testing data set; moreover, it provides detailed coefficients for many valuable parameters. LassoLarsCV also provides relatively good result, but in most cases, the only useful predictor is budget. Other models, like LarsCV, ElasticNetCV, and OrthogonalMatching- PursuitCV, didn’t provide competitive r2 in the end.

## Package 

* [scikit-learn](https://scikit-learn.org/stable/) - All the models were constructed based on the scikit-learn package

