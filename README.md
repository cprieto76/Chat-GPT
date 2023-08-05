## Chat-GPT

(https://github.com/karpathy/nanoGPT)  
https://www.youtube.com/watch?v=kCc8FmEb1nY&t=150s


- **Machine learning models**: algorithms or computational structures that are designed to learn patterns, relationships, and representations from data.

- **Deep learning models**: class of machine learning models that are designed to automatically learn and represent complex patterns and relationships in data by utilizing multiple layers of interconnected processing units, also known as neurons or nodes.

---

## NEURON
mathematical function that takes one or more inputs, applies weights to these inputs, computes a weighted sum, adds a bias term, and then passes the result through an activation function to produce an output.

![image](https://github.com/cprieto76/Chat-GPT/assets/115907710/30548509-615c-4ac6-8477-dfe3d72b5619)

- **Inputs**: Neurons receive input data, which could be features from the previous layer in a neural network, sensor measurements, or any other relevant data.

- **Weights**: Each input is associated with a weight, which determines the importance of that input in the neuron's computation. These weights are learned during the training process of the neural network.

- **Bias**: A bias term is added to the weighted sum of inputs. The bias allows the neuron to shift the decision boundary of the activation function.

- **Weighted Sum**: The weighted sum of inputs and bias is computed. This step represents the linear combination of inputs, weights, and bias.

- **Activation Function**: The weighted sum is then passed through an activation function, which introduces non-linearity to the neuron's output. Common activation functions include the Rectified Linear Activation (ReLU), sigmoid, and hyperbolic tangent (tanh).

- **Output**: The output of the activation function becomes the output of the neuron. This output is then passed to neurons in the next layer of the neural network.

## Example of a Neuron

Neuron that takes two inputs and produces an output using a step function as its activation function.

The neuron's inputs are x1 and x2, and it has corresponding weights w1 and w2. The neuron also has a bias b.  
The computation performed by the neuron can be represented as:  

![image](https://github.com/cprieto76/Chat-GPT/assets/115907710/5f24b455-a893-4c5d-a2f3-8d15c153d6a5)  

Let's assign some values to the weights and bias for this example:

![image](https://github.com/cprieto76/Chat-GPT/assets/115907710/a7dc3eb7-a27b-4320-83d3-72ce7f19157e)

Now, let's say we have input values x1=0.8 and x2=-0.4. We can plug these values into the neuron's computation:  

![image](https://github.com/cprieto76/Chat-GPT/assets/115907710/b3af8861-9172-4390-9b2c-a0013b664382)  

Since 0.72 is greater than 0, the step function will output 1. Therefore, the final output of the neuron for the given inputs is 1.

In this simple example, the neuron is making a binary decision based on the weighted sum of inputs and the bias. It activates if the weighted sum plus bias is greater than or equal to zero, and it doesn't activate otherwise.

---
- **Sequence transduction models**: type of machine learning model used for tasks that involve transforming one sequence of data into another sequence.

- **Convolutional Neural Networks (CNNs)**: class of deep learning models primarily designed for processing and analyzing grid-structured data, such as images and videos.



