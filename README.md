# CustomKNN
If you have experience working with scikit-learn's KNN algorithm, you may have observed its utilization of majority voting.

Consider a scenario where a model's K value is set to 10. In this case, for a data point to be classified as 1, it requires at least 5 of its nearest neighbors to also be labeled as 1. But what if we aim for a higher threshold, such as requiring 8 or even all 10 neighbors to have the label 1?

This class is designed to cater to such requirements and provide a solution for customizing the voting mechanism in KNN classification.

I also implemented an option that allows the user to define the K value based on the farthest neighbors, so a data point will be labeled as 1 if the votes of the K farthest neighbors are 0, and vice versa.