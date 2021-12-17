# External Resources
- [Rules of ML](https://developers.google.com/machine-learning/guides/rules-of-ml)
- [Neural Networks](https://en.wikipedia.org/wiki/Neural_network)

# Fundamentals
- **Artificial Intelligence** - Intelligence shown by computers.
- **Machine Learning** - A subset of AI which is able to learn without explicit instructions, using algorithms and statistical informations.
- **Deep Learning** - A subset of ML which uses multiple layers of processing to extract higher levels of information from data

## Programming vs Machine Learning Algorithms
Programming takes some Inputs and Rules, to create an Output

Machine Learning Algorithms takes Inputs and Expected Outputs, to get the Rules

A example of a Machine Learning Algorithm:-
We pass chest x-rays (Output) into ML Algorithms and it tells us if a person is infected with Covid-19 or not (Rules)

```md
Tip - ML can be used in literally anything if it can be converted into numbers
```

```md
Tip - If you can code a **SIMPLE** rule based system instead of an ML Algorithm, make the rule based system instead
```
## What Deep Learning is good for
1. Problems with long list of rules
2. Continously changing environments
3. Discovering things in large amounts of data

## What Deep Learning is bad for
1. When a human needs to understand the deep learning algorithm's patterns
2. When a simple rule based system is possible
3. When we cannot afford **ANY** errors
4. When you are lacking data (can usually be solved though)

# Structured Data vs Unstructured Data
- Structured Data is spread into rows and columns, like in an excel sheet
- Unstructured Data is raw data that has not been organised, for example images, social media posts, etc.

Usually ML Algorithms like Random Forest, Naive Bayes, etc. work better with Structured Data
and Deep Learning Algorithms like Neural Networks work better with Unstructured Data

*This can change depending on how we represent the problem.*

# Neural Networks
It is a network/circuit of neurons. These can be our braincells or artificial neurons in the computer.

```md
Neural Networks
├── Artificial Neural Networks
└── Biological Neural Networks
```
A neural network has an input layer which takes the data, multiple hidden layers which process the data and an output layer which outputs the data.

![neural network](./images/neuralnetwork.png)

# Types of Learning
- Supervised - Has Labels
- Semi supervised - Some Labels (the data with no labels is used for testing)
- Unsupervised - No Labels
- Transfer Learning - Using patterns from one deep learning model in another model
