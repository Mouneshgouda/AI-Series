# Learn the Underlying Techniques and Basics of Machine Learning in Python

<img width="810" height="804" alt="image" src="https://github.com/user-attachments/assets/99327804-faba-424c-8cbc-815d94cae37e" />


---

Machine learning is an application of artificial intelligence (AI) that provides systems the ability to automatically learn and improve from experience without being explicitly programmed. Machine learning focuses on the development of computer programs that can access data and use it to learn for themselves.

In this article, we’re going to learn some important techniques and tools that will help you properly use machine learning in the right way.

---

## What You Will Learn in This Article:
- History of machine learning
- Machine learning itself
- Types of Machine learning
- Applications of Machine learning
- Conclusion

---

## Brief History of Machine Learning
<img width="1387" height="692" alt="image" src="https://github.com/user-attachments/assets/0c84c597-7868-4818-914e-9d21640866c7" />


This shows that there is a deep correlation between Artificial intelligence, Machine learning, and deep learning.

Machine Learning (ML) is an important aspect of modern business and research. It uses algorithms and neural network models to assist computer systems in progressively improving their performance.

Machine Learning algorithms automatically build a mathematical model using sample data — also known as “training data” — to make decisions without being specifically programmed to make those decisions.

In this post, I will be giving a brief history of machine learning. Let’s get into the real deal.

---

### The Evolution

In 1950, Alan Turing founded the “Turing Test” to determine if a computer has real intelligence. To pass the test, a computer must be able to tease a human into believing it is also human. In 1952, Arthur Samuel wrote the first computer learning program.

The program was the game of checkers, and the IBM computer improved at the game the more it played, studying which moves made up winning strategies and incorporating those moves into its program. In 1957, Frank Rosenblatt designed the first neural network for computers (the perceptron), which simulate the thought processes of the human brain. In 1967, The “nearest neighbor” algorithm was written, allowing computers to begin using very basic pattern recognition.

This could be used to map a route for traveling salesmen, starting at a random city but ensuring they visit all cities during a short tour. In 1979, Students at Stanford University invent the “Stanford Cart” which can navigate obstacles in a room on its own. In 1981, Gerald Dejong introduces the concept of Explanation Based Learning (EBL), in which a computer analyses training data and creates a general rule it can follow by discarding unimportant data. But 2016, Google’s artificial intelligence algorithm beats a professional player at the Chinese board game Go, which is considered the world’s most complex board game and is many times harder than chess.

The AlphaGo algorithm developed by Google DeepMind managed to win five games out of five in the Go competition.

---

## Machine Learning Itself

### What is Machine Learning?

Now that we understand what machine learning is, let’s go straight into the definition aspect of this article.

Machine learning (ML) is the study of computer algorithms that improve automatically through experience. It is seen as a subset of artificial intelligence. Machine learning algorithms build a model based on sample data, known as “training data”, in order to make predictions or decisions without being explicitly programmed to do so.

According to McKinsey, he defined Machine learning as the:  
“algorithms that can learn from data without relying on rules-based programming.”

According to Arthur Samuel, he said:  
Machine learning is the ability of a computer to perform task itself without being explicitly programmed.

---

## Types of Machine Learning
<img width="850" height="460" alt="image" src="https://github.com/user-attachments/assets/ec5124eb-910e-44c6-a24b-a7d9d71df9f5" />


Machine learning can be classified into 4 types of algorithms.

- Supervised learning
- Unsupervised learning
- Semi-supervised learning
- Reinforcement learning

---

### Supervised Learning
<img width="977" height="559" alt="image" src="https://github.com/user-attachments/assets/97706f17-2f28-4e6f-acec-2a204fcfdc42" />


Supervised learning is the machine learning task of learning a function that maps an input to an output based on example input-output pairs. It infers a function from labeled training data consisting of a set of training examples.

---

#### Types of Supervised Learning

1. **Classification:**  
Classification is a type of supervised learning. It specifies the class to which data elements belong to and is best used when the output has finite and discrete values. It predicts a class for an input variable as well.  
**Example:** Spam detection, Churn prediction, Sentiment analysis e.t.c

2. **Regression:**  
Regression analysis is a subfield of supervised machine learning. It aims to model the relationship between a certain number of features and a continuous target variable.  
**Example:** Predicting stock prices, predicting prices of homes e.t.c

---

#### Supervised Machine Learning Algorithms

- K-nearest Neighbors
- Linear Regression
- Support Vector Machines
- Decision Tree
- Random Forest
- Neural Networks

---

### Unsupervised Learning
<img width="1024" height="726" alt="image" src="https://github.com/user-attachments/assets/56c90f32-e0a0-4b96-87ea-a44ed7b2a6cb" />


Unsupervised learning is a type of machine learning that looks for previously undetected patterns in a data set with no pre-existing labels and with a minimum of human supervision.

---

#### Types of Unsupervised Learning Algorithms

1. **Clustering [K-means]:**  
Clustering is a Machine Learning technique that involves the grouping of data points. In theory, data points that are in the same group should have similar properties and/or features, while data points in different groups should have highly dissimilar properties and/or features.  
**Example:** Identification of Cancer Cells e.t.c

2. **Association Rule Learning [Eclat]:**  
The ECLAT algorithm stands for Equivalence Class Clustering and bottom-up Lattice Traversal. It is one of the popular methods of Association Rule mining. This vertical approach of the ECLAT algorithm makes it a faster algorithm than the Apriori algorithm.  
**Example:** Indication of how frequently the item set appears in the database.

3. **Visualization and Dimensionality Reduction [Principal Component Analysis (PCA)]:**  
In machine learning, however, too much data can be a bad thing. Specifically, we will discuss the Principal Component Analysis (PCA) algorithm. Now, using a custom plot decision regions function, we will visualize the decision regions.

---

### Semi-supervised Learning
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/de89e0a1-2a58-46c4-930c-4fc30ca9018c" />


Semi-supervised learning is an approach to machine learning that combines a small amount of labeled data with a large amount of unlabeled data during training. Semi-supervised learning falls between unsupervised learning (with no labeled training data) and supervised learning (with only labeled training data).

Mostly, the algorithm of supervised and unsupervised learning algorithms are combined to make semi-supervised learning.

**Example:** Deep belief networks (DBNs) are based on unsupervised stack called “Restricted Boltzmann Machines (RBMs)” stacked on top of one another.

---

### Reinforcement Learning
<img width="275" height="183" alt="image" src="https://github.com/user-attachments/assets/46fe50bc-0e0e-48c2-b051-50045a6e1d5a" />

Reinforcement learning (RL) is an area of machine learning concerned with how software agents ought to take actions in an environment in order to maximize the notion of cumulative reward. Reinforcement learning is one of three basic machine learning paradigms, alongside supervised learning and unsupervised learning.

As the name implies, it is somehow more difficult. The “agent” is the learning system. In this sense, it observes the environment, selects and performs actions, and sets “rewards” in turn.

---

## Applications of Machine Learning

Machine learning is applied in every sector in the real world. Some of the applications are:

- Image Recognition: Image recognition is one of the most common applications of machine learning
- Speech Recognition
- Traffic Prediction
- Product Recommendations
- Self-driving Cars
- Email Spam and Malware Filtering
- Virtual Personal Assistant
- Online Fraud Detection e.t.c

---

## Conclusion

As we move forward into the digital age, one of the modern innovations we’ve seen is the creation of Machine Learning. This incredible form of artificial intelligence is already being used in various industries and professions.

Thanks for reading.
