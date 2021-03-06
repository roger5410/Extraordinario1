## Decision tree

Decision trees are graphical representations of possible solutions to a decision based on certain conditions, it is one of the most widely used supervised learning algorithms in machine learning and can perform classification or regression tasks (short for CART). The understanding of its operation is usually simple and at the same time very powerful.

Properly mentally decision tree structures constantly in our daily lives without realizing:

Rains? => carry an umbrella. Sunny? => wear sunglasses. I'm tired? => drink coffee. (decisions of the type IF THIS THEN THAT)

Decision trees have a first node called root (root), and then the rest of the input attributes are broken down into two branches (they could be more, but we won't get into that now) raising a condition that can be true or false. Each node is bifurcated in 2 and they are subdivided again until reaching the leaves that are the final nodes and that are equivalent to answers to the solution: Yes / No, Buy / Sell, or whatever we are classifying.

In order to obtain the optimal tree and evaluate each subdivision among all the possible trees and obtain the root node and the subsequent ones, the algorithm must somehow measure the predictions made and evaluate them to compare among all and obtain the best one. To measure and assess, it uses various functions, the most well-known and used being the "Gini Index" and "Information Gain" that use the so-called "entropy". Node division will continue until we reach the maximum possible tree depth or the nodes are limited to a minimum number of samples on each sheet.

