# Deep Learning From Scratch

A comprehensive educational repository implementing deep learning models **from scratch** using Python. This project covers fundamental neural network architectures and advanced models, helping you understand how they work at a low level.

## 📋 Overview

This repository contains Jupyter notebooks that implement various deep learning models and architectures. Each notebook provides detailed explanations of the theory and practical implementation. Perfect for students and practitioners who want to understand the math and code behind popular deep learning architectures.

## 🏗️ Project Structure

```
deep-learning-from-scratch/
├── README.md
├── requirements.txt
├── foundations/
│   └── fnn.ipynb              # Feedforward Neural Networks
└── models/
    ├── cnn_inception.ipynb     # CNN with Inception Architecture
    ├── lstm.ipynb              # Long Short-Term Memory Networks
    ├── rnn.ipynb               # Recurrent Neural Networks
    ├── transformer.ipynb       # Transformer Architecture
    └── yolo_v1.ipynb           # YOLO v1 Object Detection
```

## 📚 What's Included

### Foundations
- **FNN (Feedforward Neural Networks)**: weight initialization, forward pass, backpropagation, and gradient descent — all written by hand without any PyTorch `nn.Module`.

### Models
- **CNN with Inception**: Convolutional neural networks with the Inception module
- **RNN**: Recurrent networks for sequential data
- **LSTM**: Long Short-Term Memory networks for better long-term dependency learning
- **Transformer**: The modern transformer architecture used in NLP
- **YOLO v1**: Real-time object detection model

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook or JupyterLab

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/deep-learning-from-scratch.git
cd deep-learning-from-scratch
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Launch Jupyter:
```bash
jupyter notebook
```

5. Open any notebook and start learning!

## 📖 How to Use

Each notebook is self-contained and includes:
- **Theory**: Mathematical explanations of the model
- **Implementation**: Step-by-step code from scratch
- **Visualization**: Graphs and plots to understand model behavior
- **Examples**: Practical usage examples

Start with `foundations/fnn.ipynb` if you're new to neural networks, then explore the other models based on your interests.

## 💡 Learning Path

**Beginner:**
1. `foundations/fnn.ipynb` - Start here!
2. `models/rnn.ipynb` - Sequential data processing

**Intermediate:**
1. `models/lstm.ipynb` - Advanced sequence models
2. `models/transformer.ipynb` - Modern architectures
3. `models/cnn_inception.ipynb` - Image processing

**Advanced:**
1. `models/yolo_v1.ipynb` - Complex object detection

## 🛠️ Technologies & Libraries

Core libraries used:
- **PyTorch**: Deep learning framework
- **NumPy**: Numerical computations

## 📝 Notes

- All implementations are designed for educational purposes
- Some models may not be fully optimized for production use
- Notebooks include both mathematical derivations and code implementations
- Feel free to modify and experiment with the code!

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Add new model implementations
- Improve explanations and comments
- Fix bugs or add optimizations
- Submit pull requests

## 📄 License

This project is open-source. Please check the LICENSE file for details.

## 🔗 Resources

### Courses & Tutorials
- [Andrew Ng's Deep Learning Course](https://www.deeplearning.ai/)
- [AI Hands-on Repository](https://github.com/Ramakm/ai-hands-on)

### Research Papers
- [You Only Look Once: Unified, Real-Time Object Detection](https://arxiv.org/abs/1506.02640)
- [Going Deeper with Convolutions (Inception)](https://arxiv.org/abs/1409.4842)
- [Attention Is All You Need](https://arxiv.org/abs/1706.03762)

## ❓ FAQ

**Q: Do I need GPU to run these notebooks?**
A: No, these notebooks are designed to work on CPU. However, a GPU will significantly speed up training.

**Q: Can I use these in production?**
A: These are educational implementations. For production, consider using optimized libraries like TensorFlow or PyTorch.

---

Happy Learning! 🎓