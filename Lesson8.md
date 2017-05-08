# Lesson 8

### Perceptron
The basic unit of a neural network. In simple words, perceptron = neuron.

### Intro to neural network. Logistic Regression
In this part of the study, we analyse the criteria of acceptance at a university. It depends of two factors (the Grade and the Test of a student). But, wich one is more important? Well... the neural network will learn about it for itself. It does this with something called **weights.**

While the neural network get more training, it modify the values of the weights. Each input has a weight associated. If the final weight is near to one it means that the corresponding input is very important. If the weight is near to zero, then the corresponding input is less important. In an extreme case, if a weight is equal to zero, the input has not insidence on the neural network. No mater the value of the input, it will not affect the output of the NN (neural network).

Then I encourage you to learn more about **weights, summation and activation functions, [Heavyside step function] (https://en.wikipedia.org/wiki/Heaviside_step_function), bias**

We have been learning about different perceptrons:
- AND
- OR
- NOT
- XOR

### The simplest neural network:
- The **X1** and **X2** are the "official" inputs. **X3** is 1.
- The **W1** and **W2** are the respectives weights. The **W3** is the *bias* 
- The summation (untill now, a perceptron) works as my *hidden layer* of my neural network. 
- The **Y** is the output. But before generates the output, the input received pass through an *activation function* (example: sigmoid function).
- Finally the output.

![the simple neural network](http://3.bp.blogspot.com/-7RWgohC4pYE/VhtQ8IELsLI/AAAAAAAAA6I/_XFhMbjpcCY/s1600/Simple%2BNeural%2BNetwork.png)



### The most important topics for this lesson:
- Logistic Regression
- Neural network
- The preceptron
- Weights, Activation Function, Bias
- Sum of the squared errors (SSE)
- Mean Square Error (MSE)
- Gradient Descent
- Local minima
- Multilayer Preceptron
- BackPropagation

### More about BackPropagation
- From Andrej Karpathy: [Yes, you should understand backprop](https://medium.com/@karpathy/yes-you-should-understand-backprop-e2f06eab496b#.vt3ax2kg9)
- Also from Andrej Karpathy, [a lecture from Stanford's CS231n course](https://www.youtube.com/watch?v=59Hbtz7XgjM) **this is really good**

