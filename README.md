# GPU Graph Executor

## Objective
The goal of this project is to understand and implement a GPU graph executor capable of training simple neural networks, specifically multilayer perceptron (MLP) models. The objective is to achieve significant speedup in the training process of these models by leveraging CUDA.

## Description
The GPU Graph Executor project involves constructing a simple MLP model using a computation graph API. This model is then trained and tested on GPU to exploit parallel processing capabilities, resulting in accelerated training times.

### Key Implementations
The project includes the implementation of several key concepts and data structures to enable efficient GPU execution:

- **Shape Inference:** Perform shape inference on the computation graph based on input shapes to determine the dimensions of intermediate tensors.
  
- **GPU Executor Memory Management:** Manage memory allocation and deallocation on the GPU for efficient execution of the computation graph.
  
- **GPU Kernel Implementations:** Implement GPU kernels for common operations encountered in neural network training, such as ReLU, Matrix Multiplication (MatMul), and Softmax. These kernels are optimized for GPU execution to maximize performance gains.

---
This README.md file provides an overview of the GPU Graph Executor project, including its objective, description, and key implementations. For detailed information on usage, installation instructions, and contribution guidelines, please refer to the project documentation.