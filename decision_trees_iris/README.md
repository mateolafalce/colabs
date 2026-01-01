<div align="center">

# Decision Tree Classifier - Iris Dataset 

</div>

This repository contains a practical implementation of a **Decision Tree** using Python and the `scikit-learn` library.

This code serves as the technical demonstration for the article:
 **[Understanding Decision Trees: The White Box of Machine Learning](https://mateolafalce.github.io/2025/Understanding%20Decision%20Trees_%20The%20White%20Box%20of%20Machine%20Learning/UnderstandingDecisionTreesTheWhiteBoxofMachin.html)**

## Description

The goal of this project is to demystify how White Box algorithms work. Unlike neural networks, here we can visualize exactly the rules the model has learned to classify flowers from the **Iris** dataset.

The script performs the following:
1.  Loads the Iris dataset.
2.  Splits the data into training and testing sets (80/20).
3.  Trains a `DecisionTreeClassifier` with a limited maximum depth (`max_depth=3`) to maintain interpretability.
4.  Evaluates the model's accuracy.
5.  Exports the decision rules in text format.
