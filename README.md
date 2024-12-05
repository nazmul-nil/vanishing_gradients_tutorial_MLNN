# Understanding and Addressing Vanishing and Exploding Gradients in Deep Learning

This repository provides a tutorial to understand and address the **vanishing gradient problem** in deep learning. It includes practical solutions, such as using ReLU activation functions, proper weight initialization, and batch normalization, all demonstrated with TensorFlow.

---

## 📖 Overview

Deep neural networks often face **vanishing gradients**, where gradient values diminish during backpropagation, leading to ineffective training. This tutorial:
- Explains the vanishing gradient problem and its impact on deep learning.
- Demonstrates methods to diagnose and visualize gradient flow.
- Provides practical solutions to address this issue.

---

## 🛠️ Repository Contents

- **`tutorial\Vanishing_gradients.pdf`**: PDF tutorial with detailed explanations and visualizations.
- **`notebooks\vanishing_gradients_tutorial.ipynb`**: Jupyter Notebook with step-by-step code and output examples.
- **LICENSE**: License file outlining the terms of use.

---

## 🧰 Prerequisites

### Python Version
- Python 3.8+

### Libraries
This project uses:
- `numpy`
- `matplotlib`
- `tensorflow`

Install these libraries using:
```bash
pip install -r requirements.txt
```

---

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/nazmul-nil/vanishing_gradients_tutorial_MLNN.git
   ```
2. Navigate to the directory:
   ```bash
   cd vanishing_gradients_tutorial_MLNN
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook vanishing_gradients_tutorial.ipynb
   ```
4. Follow the notebook's step-by-step explanations and visualizations.

---

## 🔗 References

1. Bengio, Y., Simard, P., and Frasconi, P. (1994). *Learning long-term dependencies with gradient descent is difficult.* IEEE Transactions on Neural Networks, 5(2), pp.157–166.
2. Hochreiter, S., Bengio, Y., Frasconi, P., and Schmidhuber, J. (1997). *Gradient flow in recurrent nets: The difficulty of learning long-term dependencies.* A Field Guide to Dynamical Recurrent Neural Networks, pp.237–243.
3. Pascanu, R., Mikolov, T., and Bengio, Y. (2013). *On the difficulty of training recurrent neural networks.* In International Conference on Machine Learning, pp.1310–1318.
4. Rumelhart, D.E., Hinton, G.E., and Williams, R.J. (1986). *Learning representations by back-propagating errors.* Nature, 323(6088), pp.533–536.
5. Nair, V. and Hinton, G.E. (2010). *Rectified linear units improve restricted Boltzmann machines.* Proceedings of the 27th International Conference on Machine Learning (ICML), pp.807–814.
6. Glorot, X. and Bengio, Y. (2010). *Understanding the difficulty of training deep feedforward neural networks.* Proceedings of the 13th International Conference on Artificial Intelligence and Statistics (AISTATS), pp.249–256.
7. Ioffe, S. and Szegedy, C. (2015). *Batch normalization: Accelerating deep network training by reducing internal covariate shift.* Proceedings of the 32nd International Conference on Machine Learning (ICML), pp.448–456.

---
