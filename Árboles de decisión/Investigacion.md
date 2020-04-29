## Decision tree

Decision trees build classification or regression models with a tree-like structure. Break a dataset down into smaller and smaller sets, while building an increasingly developed decision tree. The end result is a tree with decision nodes and leaf nodes. A decision node (eg forecast / outlook) has two or more leaves (eg Sunny, Cloudy, Rainy). A leaf node (eg Play) represents the classification of a decision. The first top node of a tree corresponds to the best prediction called the root node. Decision trees support both numerical and categorical data.

Algorithm

The base algorithm for building decision trees is called ID3 created by J.R. Quinlan, and employs an ambitious downward search through all possible tree branches without backtracking. The ID3 algorithm uses the Entropy Gain and Information to build the decision tree.

In the ZeroR model there are no predictors, in the UnR model we try to find the best predictor of all, with Bayes Basic we include all the predictors using the Bayes rule and the independent assumptions between the predictors, but with the decision tree we include all the predictors with the assumption of dependency between them.


