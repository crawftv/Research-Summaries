[Source for the paper here](https://arxiv.org/abs/1904.01983)

## One neuron is more informative than a deep neural network for aftershock pattern forecasting
#### Arnaud Mignan, Marco Broccardo
### A Summary
Despite promising headlines "DL does not improve prediction compared to simpler baseline models"
The paper compares published results of a DL model a logistic model. 
The Deep Neural Network used 12 variables, 6 layers, and 50 nodes for 13,451 parameters. The  Logistic model simulated a 1 node NN with 1 input and 2 free parameters. y=mx+b.
Both models achieved an AUC score of 0.85. 
Adding one more parameter to the logistic model increased AUC to 0.86.
### "Deep Learning does not improve perdiction compared to simpler baseline models."
#### Why?
Over engineering. The DNN used engineered variables. 
"The stress tensor is not measured, but estimated on the basis of different assumptions or assumed quantities, some of which are affected by large uncertainties.
The authors state, "DL should be used directly on observable and measured variables." Feature engineering, assumptions in variables, and hidden assumptions in DNN's equals poor models. Its assumptions all the way down. 
The AUC score for Logistic Regression was already available in the literature.
