### Ethics: Bias Analysis (Short Answer)

AI models can behave unfairly if the data used to train them is biased.  
For example, text sentiment models trained on Amazon reviews may learn certain biased language patterns such as overly positive or negative words associated with certain product categories, cultures, or writing styles.  
Image models like MNIST are less risky but can still fail when digits are written in different cultural styles or by people with different handwriting patterns.

To reduce bias, developers should:
- evaluate models on diverse test data,
- check performance gaps across sub-groups,
- visualize misclassifications,
- and use fairness tools such as Google’s “Fairness Indicators.”
