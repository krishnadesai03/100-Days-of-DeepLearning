# Day 2 – Neural Networks & History of Deep Learning  
## 100 Days of Deep Learning 🚀

---

# What is a Neural Network?

A Neural Network is a computational model inspired by the human brain.  
It consists of layers of interconnected nodes called **neurons**.

Each neuron:
1. Takes inputs  
2. Applies weights  
3. Adds a bias  
4. Passes the result through an activation function  
5. Produces an output  

Mathematically:

output = Activation( (w1x1 + w2x2 + ... + wnxn) + b )

Where:
- w = weights  
- x = inputs  
- b = bias  

---

# Structure of a Neural Network

### 1️⃣ Input Layer
- Receives raw data (features)

### 2️⃣ Hidden Layers
- Perform computations
- Extract patterns
- The more hidden layers → the "deeper" the network

### 3️⃣ Output Layer
- Produces final prediction
  - Regression → Continuous value
  - Classification → Probability / Class label

---

# Activation Functions

Activation functions introduce **non-linearity**, allowing neural networks to learn complex patterns.

Common activation functions:

- **ReLU (Rectified Linear Unit)** → max(0, x)
- **Sigmoid** → Outputs values between 0 and 1
- **Tanh** → Outputs values between -1 and 1
- **Softmax** → Used for multi-class classification

Without activation functions, neural networks would behave like simple linear models.

---

# How Neural Networks Learn

Neural networks learn using:

### 1️⃣ Forward Propagation
- Data passes through the network
- Prediction is generated

### 2️⃣ Loss Function
- Measures prediction error
- Example: Mean Squared Error, Cross Entropy

### 3️⃣ Backpropagation
- Calculates gradients
- Updates weights using Gradient Descent

Goal:
Minimize loss by adjusting weights.

---

# Brief History of Deep Learning

## 1943 – First Artificial Neuron
- Warren McCulloch & Walter Pitts proposed a mathematical model of a neuron.

## 1958 – Perceptron
- Introduced by Frank Rosenblatt.
- Could classify linearly separable data.

## 1969 – AI Winter Begins
- Marvin Minsky showed perceptrons couldn’t solve XOR.
- Funding and research slowed down.

## 1986 – Backpropagation Revival
- Geoffrey Hinton and others popularized backpropagation.
- Neural networks became trainable effectively.

## 1998 – CNN (LeNet)
- Yann LeCun developed Convolutional Neural Networks for digit recognition.

## 2006 – Deep Learning Revival
- Hinton introduced deep belief networks.
- Interest in multi-layer neural networks returned.

## 2012 – ImageNet Breakthrough
- AlexNet dramatically outperformed others in image classification.
- Sparked the modern deep learning revolution.

## 2017 – Transformers
- “Attention is All You Need” paper introduced Transformers.
- Foundation for modern LLMs like GPT.

## Present
- Deep learning powers:
  - ChatGPT
  - Autonomous vehicles
  - Medical AI
  - Computer vision
  - Generative AI

---

# Key Differences: Early NN vs Modern Deep Learning

| Early Neural Networks | Modern Deep Learning |
|----------------------|----------------------|
| Shallow networks | Deep multi-layer networks |
| Limited compute | GPU/TPU acceleration |
| Small datasets | Massive datasets |
| Slow training | Optimized frameworks (PyTorch, TensorFlow) |

---

# Key Takeaways – Day 2

- Neural networks are inspired by the brain.
- They consist of layers of weighted neurons.
- Activation functions introduce non-linearity.
- Backpropagation enables learning.
- Deep learning has evolved over decades with major breakthroughs.
- 2012 marked the modern deep learning boom.

---

🔥 Day 2 Complete!