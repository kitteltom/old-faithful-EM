# Expectation Maximization for Gaussian Mixtures

The following figure demonstrates Expectation Maximization (EM) for Gaussian Mixtures on the *Old Faithful* dataset. (*Old Faithful* is a famous geyser in Yellowstone National Park, US.)

![EM](out/EM.gif)

Plotting the waiting time between eruptions over eruption time reveals a "cluster" structure. In this project I model this structure with a Gaussian Mixture Model. To find appriximate cluster centers k-Means Clustering is used. Equations and algorithms can be found in `EM_gaussian_mixture.ipynb`. 

This project is based on an assignment from the lecture [Probabilistic Machine Learning](https://www.youtube.com/playlist?list=PL05umP7R6ij1tHaOFY96m5uX3J21a6yNd) at the [University of Tübingen](https://uni-tuebingen.de/).
