# Applying the Analog Hardware Acceleration Kit for In-memory Computing Design
### Final Project 3 - ECSE-541 McGill University

## Abstract
Deep Neural Networks (DNNs) have achieved promising progress in many complex tasks, including image or speech recognition, gaming, and real-time language responses. Training of large DNNs, however, is still considered a time-consuming and computationally intensive task that demands extra high computational resources for many days. Analog based devices have shown great potential to break von Neumann’s bottleneck and potentially accelerate DNN training by orders of magnitude while using much less power. Nevertheless, the non-ideality problem still remain a daunting problem when implementing analog devices in in-memory computing design. Recently proposed IBM’s analog hardware acceleration kit provides us a window for the simulation of non-idealities of analog devices. In this paper, the IBM tool is utilized to simulate Resistive Processing Units (RPUs) to represent weights and biases value in Fully-Connected Neural Network (FCNN). MNIST dataset is applied to the Analog FCNN. By performing optimization on hyperparameters such as activation functions, batch size, and learning rate, 100% testing accuracy could be achieved even with considering noise with SNR = 30 db. Moreover, computation cost and the performance is also examined. The result shows that even by applying only 3 layered neural networks (784-128-10), 95% accuracy can be achieved with only 3% decrements compared to the deeper ones.

## Code Usage - (Python 3.6, Colab)
1. Please Upload to python notebook (.ipynb file) to Colab
2. Choose GPU as runtime type
3. Enjoy it :)

