# Basic Python Neural Network

A simple 2-layer neural network implementation in Python that learns the XOR function using backpropagation.

## 📖 About

This project demonstrates the fundamentals of neural networks and backpropagation through a minimal Python implementation. The network learns to solve the XOR problem, a classic example that requires a hidden layer to solve.

## 🧠 How It Works

- **Input Layer:** 3 neurons (2 inputs + 1 bias)
- **Hidden Layer:** 4 neurons
- **Output Layer:** 1 neuron
- **Activation Function:** Sigmoid
- **Training:** 60,000 iterations using gradient descent

### XOR Truth Table

| Input 1 | Input 2 | Output |
|---------|---------|--------|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

## 🚀 Usage

### Prerequisites

- Python 3.x
- NumPy

### Installation

```bash
pip install numpy
```

### Run

```bash
python neural_network.py
```

### Expected Output

```
Error:0.4964100319027255
Error:0.008584525653247157
Error:0.005789459862507806
Error:0.004629176776769983
Error:0.003958765280273646
Error:0.0035101225678616736
Final Output after Training:
[[0.00260572]
 [0.99672209]
 [0.99701711]
 [0.00386759]]
```

## 📚 Credits

This project was built following the excellent tutorial by **Andrew Trask**:

**[A Neural Network in 11 lines of Python (Part 1)](https://iamtrask.github.io/2015/07/12/basic-python-network/)**

> *"A bare bones neural network implementation to describe the inner workings of backpropagation."*

## 📄 License

This project is open source and available for educational purposes.
