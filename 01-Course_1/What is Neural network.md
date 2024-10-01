https://www.coursera.org/learn/neural-networks-deep-learning/lecture/eAE2G/what-is-a-neural-network#

### Neural Networks and Housing Price Prediction 🏠📈

- **Neural Network Basics:**  
  A neural network is used to **predict outcomes** like housing prices. It's a function that maps an **input** (e.g., house size) to an **output** (e.g., house price). 🧠

- **Simple Neural Network Example:**
  - Input: Size of the house 🏡
  - Output: Predicted price 💰
  - The function fits a curve (like a straight line with adjustments) to ensure prices don't go negative.

- **Neuron Function (ReLU):**  
  - The neuron uses a **ReLU** (Rectified Linear Unit) function, which:
    - Outputs 0 for negative values
    - Outputs the input value for positive numbers ➡️ (max(0, x))
  - ReLU is a common function in neural networks and helps create non-linear relationships. 📈

### Building Larger Neural Networks 🧩🔗

- **Expanding Inputs:**  
  In more complex models, other features like **number of bedrooms**, **family size**, **zip code**, and **walkability** can also influence the price. These additional features are inputs to a larger neural network. 🛠️

- **Lego Brick Analogy:**  
  Each **neuron** (like a ReLU unit) is like a **Lego brick**. Stacking many neurons together builds a more complex and powerful network. 🧱

### Fully Connected Layers 🔄

- **Dense Layers:**  
  In a larger neural network, each **input** (e.g., size, bedrooms, zip code) is connected to every **hidden unit** (neurons in the middle layers). These hidden units figure out relationships between the inputs and the output. 🌐

- **Training Process:**  
  You provide the neural network with **input (x)** and **output (y)** examples from your dataset, and the network learns to **map x to y** (e.g., predict house prices). 🎯

### Neural Networks in Supervised Learning 🎓

- Neural networks excel in **supervised learning**—where the goal is to map an input to an output (like predicting a value). It's especially powerful with enough training data. 📊
