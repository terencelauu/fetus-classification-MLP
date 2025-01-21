# Fetus Classification using Multilayer Perceptron (MLP)

This project demonstrates the use of deep learning for classifying fetal health based on medical or ultrasound data. Using a Multi-Layer Perceptron (MLP) architecture implemented in PyTorch, the project performs preprocessing, training, and evaluation on a given dataset. It also explores hyperparameter optimization using random search for improved performance.

### Key Features
Preprocessing Pipeline: Includes label encoding and standardization of input features.

Configurable MLP Model: Allows flexible architecture tuning with multiple hidden layers and neurons.

Training and Evaluation: Provides real-time tracking of loss and accuracy during training and testing.

Hyperparameter Tuning: Implements random search to optimize batch size, learning rate, and model architecture.

Results Visualization: Demonstrates the impact of different configurations on model performance.
Here is the table in text format:

### Result
| **Experiment** | **Batch Size** | **Hidden Size** | **Hidden Layers** | **Learning Rate** | **Test Accuracy (%)** |
|-----------------|---------------|-----------------|-------------------|-------------------|-----------------------|
| 1               | 64            | 200             | 1                 | 0.00090081        | 74.14                 |
| 2               | 32            | 200             | 1                 | 0.00501029        | 70.69                 |
| 3               | 128           | 200             | 1                 | 0.00748149        | 72.41                 |
| 4               | 32            | 200             | 2                 | 0.00070867        | 74.14                 |
| 5               | 64            | 50              | 1                 | 0.00029804        | 68.97                 |

<br> 

![image](https://github.com/user-attachments/assets/c38d7df1-888c-46c3-838b-6c864023f94e)
