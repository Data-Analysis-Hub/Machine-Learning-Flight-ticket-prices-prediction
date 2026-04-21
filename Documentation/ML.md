## Bunch of definitions:

* variance is a statistical measure of the dispersion of our data, used widely & frequently in machine learning to understand the data distribution
* unsupervised learning is a type of machine learning where the algorithm learns from unlabelled data often used for clustering or anomaly detection
* clustering is an unsupervised machine learning technique where the algorithm learns to group data based on similar characteristics without predefined labels.
* time series analysis is the analysis of ordered temporal data used for forceasting & trend analysis;
* transfer learning is applying learned knowledge from task A to a different but related task B which is used to improve model's performance
* gradient descent is an optimization algorithm used to find the local minimum of a function by adjusting it's parameters in the opposite direction of the gradient to minimize the cost function (error)
* stochastic gradient descent is a variant of gradient descent that updates the model's parameters using single data point on each iteration.
* sentiment analysis is the use of natural language processing to categorize opinions expressed in text
* regression is the statistical method to map the relationship between a dependent variable & one or more independent ones; (independent variables are inputs whereas dependent variable is the output we're studying) 
* regularization is method, to prevent overfitting by adding a penalty term to the loss function
* logistic regression is used for binary classification problems to model the probability of a particular class.
* linear regression is a method for analyzing linear relationship between a dependet variable & one or more independent ones.
* reinforcment learning is a type of learning that lets a model learn by interacting with an environment to achieve a goal
* decision trees are a type of supervised learning that makes decision based on splitting data along a feature value
* random forest is just multiple decision trees that outputs the average prediction of the individual tree for regression tasks or a class that receive the most votes.
* truncation is the process of limiting the number of elements in dataset or number of nodes in a Neural Network
* Principla component analysis is a dimensionality reduction technique that transforms the original variable into a new sets of uncorrelated variables
* pre-training is the first phase of training a machine learning model on a large dataset before fine tuning it on a specific task
* oversampling is a technique used to balance a class distribution by duplicating the minority class 
* overfitting is a modeling error that occurs when the model captures noise in the training data; failing to generalize against new unseen data.
* one hot encoding is the representation of categorical variables as binary vectors
* nearest neighbors search is the algorithm used to find the nearest points in a dataset given a data point
* normalization is a the process of scaling the featurs to a standard range to improve model's performance
* NLP is a field that focuses on the interaction between computers & human language
* matrix factorization is a technique used to decompose a matrix into multiple matrices 
* markov chains is a stochastic model that represents the possibility of each event & it's probability based on the previous event state
* model selection is choosing the most appropriate machine learning algorithm for a specific task :!important:
* model evaluation is the process of assessing the performance of a model by specific metrics
* knowledge graphs is representation of facts & relationships between elements & actors.
* joint probability is the probabiltity of multiple events occuring together, used in probabilistic models.
* inductive bias is the generalizations & assumptions made by the model to reason through unseen data from the trained data
* inference is the process of making predictions using trained models
* imbalanced data is where a certain class or set of classes are dominating the dataset, this requires handling techniques to be used against the model
* human in the loop is technique that involves the human interaction with the model.
* vanishing gradient is a problem in training neural networks where the gradients become too small for effective weight updates. 
* generalization is the ability of the model to perform well on unseen data.
* Generative Adversarial Networks is a class of machine learning frameworks where two neural networks (a generator & a discriminator) are trained together, used commonly in image generation tasks.
* ensemble methods are techniques to combine multiple models to improve the overall performance.
* multiclass classification is where the specific samples can belong to 1 out of 3 or more classes, unlike the binary classification that classifies the sample from 1 of the 2 classes.
* data preprocessing is the initial steps to prepare & clean data before fitting it into a machine learning model
* regression analysis is a statistical process for estimating the relationships among variables used in predictive modeling 
* sigmoid function is an activation function that outputs values between 0 & 1 (used in logistics regression)   
* evolutionary algorithms are optimization algorithms inspired by the process of natural selection used in machine learning or parameter tuning. 
* language models are statistical models that predict the next element (word) in a sequence of words
* backpropagation is an optimization algorithm used to minimize the loss function by adjusting the model's weights 
* bagging an ensemble technique where we train the model on the set by subsetting the original set into subsets & train it on those subsets 
* dense vector is a type of vector that most of the elements in it are non-zero, used in data science for feature representation & various computation 
* feature engineering is transforming raw data into a format that makes it easier for machine learning algorithms to interpret
* support vector machines are supervised learning algorithms used for classification & regression tasks that find the hyperplane that best seperates different classes in the **feature space**
* cross validation (K-Fold) is a technique for assessing the performance of a ML Model by dividing the dataset into multiple subsets & evaluating the model on different combination of these subsets
* loss function is a mathematical function that quantifies the predicted & actual outcomes in machine learning algorithms, the goal is to always minimize the loss function
* pvalue is a measure used in hypothesis testing to indicate the probability of observing a statistic test as extreme as the one computed given that the null hypothesis is true.
* ttest is a statistical test used to compute the mean of two groups & determine if they are significantly from each other
* (not-relevant) cosine similarity is a metric used to measure the cosine of the angle between 2 non-zero vectors in an inner product space 
* dropout is a regularization technique in neural networks where random selected neurons are ignored during training to prevent the overfitting problem 
* softmax is an activation function that turns raw scores into probabilities often used in the output layer of a classification of a neural network
* bayes theorem is a principle in probability theory & statistics that describes the probability of an event based on prior knowledge of related conditions.
* tanh function is an activation function used in neural networks that scales the output to be in the range of -1 & 1
* ReLU (Rectified Linear Unit) function is a nonlinear activation function used in neural networks that output the input if it's positive or 0 otherwise.
* Mean Squared Error (MSE) function is a loss function used in regression problems that measures the average
* the Root Mean Square Error (RMSE) provides the average magnitude of the errors 
* R-Squared (coefficient of determination) is a statistical measure indicating the proportion of the dependent variables variance that is explained by the independent variable or variables in a regression model
* L1/L2 regularization are techniques that add penalty terms to the loss function to prevent overfitting with L1 leading to sparse solutions & L2 shrinks the weights
* Learning Rate is a tuning parameter in an optimization algorithm that determines the step size at each iteration while moving towards the minimum of the loss function, metaphorically shows the speed at which the ML Model learns 
* Cost function it measures the cost or loss of the model's prediction compared, the optimization is to minimize the result of this loss function 
* confusion/error matrix is a specific table that allow visualization of the performance of an algorithm, each row represent the instances of an actual class, & each column is the instances of a predicted class.
* precision/recall, precision is the fraction of relevant instances amongst the retrieved instances reflecting the accuracy of the model in classifying positive instances while recall, also known as sensitivity is a fraction of relevant instances that were retrieved indicating the ability of the ML Model to retrieve relevant instances
*  Area Under the Curve of the Reciever Operating Characteristic (AUR-ROC): is a performance measurement for classification problems representing the probability that a model will rank a randomly chosen positive instance higher than a randomly chosen negative one providing an aggregate measure of model performance across different classification 
* train-test split, this is what we do for machine learning, splitting dataset into 2 one for training & one for testing & evaluating the model's performance known as the test set.
* grid search also called parameter sweep is used for hyperparameter optimization & it's done by exaustively searching through a manually specified subset of hyper parameters of an ML Algorithm
* anomaly detection is detection of data points that don't follow the majority of the data, significantly deviated 
* missing values should be handled using either imputation, emission or direct analysis methods to mitigate biases & innaccuracies.

______

supervised is where the ML Model has an idea about what the data is & what's about, it's labeled or we show it how a sample of the data looks like & what it is, then it trains on that, unsupervised it no intervention occurs from our side & we let it decide how it'll work; from classifying data by similarity characteristics.

for supervised learning there's 2 categories , regression & classification;
in regression we want to predict 

# Resources:
(https://www.youtube.com/watch?v=PcbuKRNtCUc)[first video] # unfinished
(https://www.youtube.com/watch?v=E0Hmnixke2g)[second video]

