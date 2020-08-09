# Challenge Analysis

I started with a model of just 1 hidden layer and 3 nodes in that layer to start with a relatively simply approach and allow room to add complexity as needed. My hope was that this would prevent overfitting and make the model more generizable.

I was not able to achieve a target of 75% accuracy, but I did get close at ~73% 
I tried multiple different attempts to increase the performance.
First, I added an additional hidden layer with 2 nodes to the model. This did not significantly improve the model.
Second, I increased the number of neurons in each layer. This also did not significantly improve the model.
Third, I tried changing the hidden layer activation functions to tanh from relu. This added a small improvement to the model.
Fourth, since none of the optimization above significantly improved the model, I hypothesized that the input data was not optimized. I thought that application type and government classification were inputs that may not add value to the model so therefore I tried altering the input data by removing these categories and then recreating the deep learning model. This also did not significantly improve the model.

If I were to start over, I would try a using a random forrest classifier instead of a deep learning model since this is tabular data. A primary benefit to this approach would be significantly less coding and faster training and evaluation.
