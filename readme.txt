#The project aimed to achieve text classification using deep learning methodologies and continuously improve classification performance through the optimization of network architecture and training processes. 

The goal of this project is to develop a Feedforward neural network for topic classification.
For that purpose, the process is:
• Text processing methods for transforming raw text data into input vectors for Ir network
• A Feedforward network consisting of:
– One-hot input layer mapping words into an Embedding weight matrix 
– One hidden layer computing the mean embedding vector of all words in input fol-
lowed by a ReLU activation function 

– Output layer with a softmax activation. 
• The Stochastic Gradient Descent (SGD) algorithm with back-propagation to learn the
weights of Ir Neural network. Ir algorithm should:
– Use (and minimise) the Categorical Cross-entropy loss function 
– Perform a Forward pass to compute intermediate outputs
– Perform a Backward pass to compute gradients and update all sets of weights 
– Implement and use Dropout after each hidden layer for regularisation 

•  how did I choose hyperparameters? 
I can tune the learning rate (hint: choose
small values), embedding size {e.g. 50, 300, 500}, the dropout rate {e.g. 0.2, 0.5} and the
learning rate.

• Re-train Ir network by using pre-trained embeddings (GloVe) trained on large corpora.
Instead of randomly initialising the embedding weights matrix, I should initialise it with
the pre-trained weights. During training, I should not update them (i.e. weight freezing) and backprop should stop before computing gradients for updating embedding weights.
Report results by performing hyperparameter tuning and plotting the learning process.

• Extend Feedforward network by adding more hidden layers (e.g. one more or two).
Note: I need to repeat hyperparameter tuning, but the number of combinations grows exponentially. Therefore, I need to choose a subset of all possible combinations 
• Provide well documented and commented code describing all of Ir choices. In general,
text processing (e.g. punctuation, numbers, vocabulary size) and hyperparameter values. 
