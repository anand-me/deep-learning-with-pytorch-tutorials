# Deep Learning with PyTorch Tutorials

<div align="center">
  <img src="https://pytorch.org/assets/images/pytorch-logo.png" alt="PyTorch Logo" width="400"/>
  
  <p>
    <a href="https://github.com/anand-me/deep-learning-with-pytorch-tutorials/stargazers">
      <img alt="GitHub stars" src="https://img.shields.io/github/stars/anand-me/deep-learning-with-pytorch-tutorials?style=for-the-badge&color=yellow">
    </a>
    <a href="https://github.com/anand-me/deep-learning-with-pytorch-tutorials/network/members">
      <img alt="GitHub forks" src="https://img.shields.io/github/forks/anand-me/deep-learning-with-pytorch-tutorials?style=for-the-badge&color=blue">
    </a>
    <a href="https://github.com/anand-me/deep-learning-with-pytorch-tutorials/issues">
      <img alt="GitHub issues" src="https://img.shields.io/github/issues/anand-me/deep-learning-with-pytorch-tutorials?style=for-the-badge&color=red">
    </a>
    <a href="https://github.com/anand-me/deep-learning-with-pytorch-tutorials/pulls">
      <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/anand-me/deep-learning-with-pytorch-tutorials?style=for-the-badge&color=green">
    </a>
  </p>

  <h3>A comprehensive tutorial series for learning Deep Learning with PyTorch from fundamentals to deployment</h3>

  <p>
    <a href="#-about">About</a> •
    <a href="#-tutorials">Tutorials</a> •
    <a href="#-prerequisites">Prerequisites</a> •
    <a href="#-getting-started">Getting Started</a> •
    <a href="#-contributing">Contributing</a> •
    <a href="#-license">License</a> •
  </p>
</div>

## 🚀 About

Welcome to the **Deep Learning with PyTorch Tutorials** repository! This educational project provides a structured learning path from basic tensor operations to model deployment in production. Each tutorial builds upon knowledge from previous chapters, creating a comprehensive deep learning curriculum.

Developed by **Akshay Anand** as part of PhD research at **Florida State University**, these tutorials combine theoretical explanations with practical code examples to enhance understanding of deep learning concepts.

### ✨ Features

- **Comprehensive Coverage**: From basics to advanced topics
- **Mathematical Foundations**: Strong focus on theoretical underpinnings
- **Practical Implementation**: Executable code examples
- **Visual Learning**: Clear diagrams and visualizations
- **TensorBoard Integration**: Advanced visualization capabilities
- **Deployment Focus**: Techniques for real-world applications

## 📚 Tutorials

This series consists of five interconnected tutorials that guide you from foundational concepts to advanced model deployment:

### 1. Introduction to Tensors
- Understanding Tensors
- Basic Tensor Operations
- Tensor Manipulation
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anand-me/deep-learning-with-pytorch-tutorials/blob/main/PyTorchTuto_1.ipynb)

### 2. Autograd and Automatic Differentiation
- Understanding Gradients
- Computational Graphs
- Gradient Tracking and Management
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anand-me/deep-learning-with-pytorch-tutorials/blob/main/PyTorchTuto_2.ipynb)

### 3. Neural Networks with PyTorch
- PyTorch's nn Module
- Building Neural Network Layers
- Creating Complete Network Architectures
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anand-me/deep-learning-with-pytorch-tutorials/blob/main/PyTorchTuto_3.ipynb)

### 4. Training Models
- Loss Functions
- Optimizers
- Training Loops
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anand-me/deep-learning-with-pytorch-tutorials/blob/main/PyTorchTuto_4.ipynb)

### 5. Saving and Loading Models
- Model Serialization
- Loading Pretrained Models
- Model Deployment Basics
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anand-me/deep-learning-with-pytorch-tutorials/blob/main/PyTorchTuto_5.ipynb)

### 🔍 Each tutorial includes:

- **Detailed Theory**: Mathematical foundations and concepts
- **Code Examples**: Executable implementation examples
- **Visualizations**: Diagrams and TensorBoard integrations
- **Practical Tips**: Best practices for real-world applications

## 🛠 Prerequisites

To get the most out of these tutorials, you should have:

- Basic Python programming knowledge
- Elementary understanding of calculus and linear algebra
- A computer with Python 3.7+ installed

## 🏁 Getting Started

### Option 1: Run on Google Colab (Recommended for beginners)

Each tutorial has an "Open in Colab" badge that allows you to run it directly in your browser:

| Tutorial | Open in Colab |
|----------|---------------|
| 1. Introduction to Tensors | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anand-me/deep-learning-with-pytorch-tutorials/blob/main/src/PyTorchTuto_1.ipynb) |
| 2. Autograd and Automatic Differentiation | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anand-me/deep-learning-with-pytorch-tutorials/blob/main/src/PyTorchTuto_2.ipynb) |
| 3. Neural Networks with PyTorch | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anand-me/deep-learning-with-pytorch-tutorials/blob/main/src/PyTorchTuto_3.ipynb) |
| 4. Training Models | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anand-me/deep-learning-with-pytorch-tutorials/blob/main/src/PyTorchTuto_4.ipynb) |
| 5. Saving and Loading Models | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anand-me/deep-learning-with-pytorch-tutorials/blob/main/src/PyTorchTuto_5.ipynb) |

Running in Colab gives you:
- Free GPU/TPU access
- No local setup required
- Easy sharing and collaboration

### Option 2: Local Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/anand-me/deep-learning-with-pytorch-tutorials.git
   cd deep-learning-with-pytorch-tutorials
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

## 📦 Installation Requirements

To ensure a smooth experience, this repository includes both `requirements.txt` and environment YAML files for flexible setup options:

### Option 1: Using pip
```bash
pip install -r requirements.txt
```

### Option 2: Using conda
```bash
conda env create -f environment.yml
conda activate pytorch-tutorials
```

### Running the Notebooks
```bash
jupyter notebook
# or
jupyter lab
```

Navigate to the `src` directory and open the desired notebook.

## ✨ Key Features

These tutorials stand out due to their:

- **Visual Learning Approach**: Complex concepts explained through intuitive visualizations
- **Code-First Philosophy**: Learn by doing with executable examples
- **Progressive Complexity**: Start simple and gradually tackle more complex topics
- **TensorBoard Integration**: Advanced visualization of model training
- **Real-world Applications**: Examples that go beyond toy datasets
- **Mathematical Foundations**: Clear explanations of the theory behind the code

## 👥 Who Is This For

These tutorials are designed for:

- **Students** seeking to understand deep learning fundamentals
- **Researchers** transitioning to PyTorch from other frameworks
- **Professionals** looking to implement deep learning in production
- **Enthusiasts** who want to explore AI/ML concepts

Whether you're a beginner or have experience with other frameworks, these tutorials provide valuable insights into PyTorch's capabilities.

## 🤝 Contributing

Contributions are welcome and greatly appreciated! Here's how you can help:

- **Report bugs**: Open an issue if you find errors or problems
- **Suggest enhancements**: New tutorials, clearer explanations, or additional examples
- **Submit pull requests**: Improve code, fix typos, or add content

Please check the [CONTRIBUTING.md](CONTRIBUTING.md) file for detailed guidelines.

## 🙏 Acknowledgements

These tutorials wouldn't be possible without:

- The **PyTorch team** for creating an amazing framework
- The **open-source community** for valuable feedback and contribution

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---



<p align="center">
  <a href="https://github.com/anand-me/deep-learning-with-pytorch-tutorials/stargazers">
    <img src="https://img.shields.io/github/stars/anand-me/deep-learning-with-pytorch-tutorials?style=social" alt="GitHub Repo stars">
  </a>
</p>

<p align="center">
  <a href="https://github.com/anand-me/deep-learning-with-pytorch-tutorials/stargazers">
    <img src="https://media.giphy.com/media/3o7abKhOpu0NwenH3O/giphy.gif" width="200" alt="Star the repo">
  </a>
</p>

<p align="center">
  ⭐ **Love this project?** Please consider giving it a **star** to support us! ⭐
</p>




<p align="center">
  <img src="https://pytorch.org/assets/images/logo-dark.svg" alt="PyTorch Icon" width="30"/>
  Created with ❤️ by <a href="https://github.com/anand-me">Akshay Anand</a>
</p>