# scikit-learn-Mine-Detection
A program that uses a k-nearest neighbors model to predict the correct time of mine.


Data set used:
https://www.kaggle.com/datasets/ritwikb3/land-mines-detection

Reasons for using this model:

Simplicity: k-NN is a simple, easy-to-understand algorithm that requires minimal tuning. This makes it a good starting point for any machine learning project, including landmine detection.

Non-Parametric Nature: k-NN doesn't make any assumptions about the underlying distribution of data. This is beneficial in landmine detection where the distribution of 'landmine' vs 'no landmine' might be highly complex or unknown.

Adaptability: k-NN can adapt to changes in the environment. As new data points are added, the algorithm can adapt to new patterns without needing to be entirely retrained. This is critical in scenarios like landmine detection where 
the environment can change over time.

Robustness to Noisy Data: By taking a majority vote from its 'k' nearest neighbors, the algorithm can be somewhat resistant to noise or anomalies. Noise is a common issue in sensor data, which is often used in landmine detection.
