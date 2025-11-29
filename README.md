# Brain-Tumor-Detection-using-CNN
DESCRIPTION OF THE DATASET
The dataset has 253 samples, which are divided into two classes with tumor and non-tumor. The number of people with brain tumor is 155 and people with non-tumor is 98.
This dataset is available on Kaggle - https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection

#  Classification Algorithm Using Machine Learning 
Before the CNN model can learn to differentiate between the images that are fed to it, it must first extract characteristics from each image. A multi-layered CNN model is suggested in this study. Brain tumors are categorized into several groups using classification algorithms. Activation functions, pooling, convolutional layers, and fully linked layers are the fundamental components of convolutional neural networks. The input data must pass through a number of phases in order to enhance the outcomes in the CNN network's output.

To develop our suggested model, we make use of PyTorch and the Anaconda environment:

Advantages of PyTorch for CNN Development:
•	PyTorch provides a wide range of pre-built modules and utilities specifically designed for CNN development, such as convolutional layers, pooling layers, and activation functions.
•	Its automatic differentiation feature allows developers to easily compute gradients and perform backpropagation, simplifying the process of training complex CNN architectures
•	It provides a flexible and intuitive interface for building and training neural networks.
               Anaconda Environment for Python Development:
•	Anaconda is a popular open-source distribution of Python and R     programming languages for scientific computing and data science.
•	It simplifies package management and dependency resolution by     providing a convenient package manager called conda.
•	Anaconda environments enable developers to create isolated Python environments with specific versions of packages and dependencies, ensuring reproducibility and avoiding conflicts between different projects.

  #   Integration of PyTorch and Anaconda:
•	Using PyTorch within an Anaconda environment combines the advantages of both tools, providing a seamless and efficient workflow for developing CNN models.
•	Developers can leverage Anaconda's environment management features to create separate environments for different CNN projects, enabling clean and isolated development environments for each project.

These process steps represent the hidden layers of the neural network and are used to perform the CNN model. Some definitions and roles of these layers are described below:
• Convolutional layer Is the primary layer of a convolutional neural network, which is consists of a filter for the input data, a feature map, and a feature detector known as the CNN core, whose function is to identify and extract the features in the picture, such as edges and colors.
 • The Pooling layer The spatial variance attribute allows Maxpooling to educate the neural network that, despite possible variations in the dimensions, textures, and presentation of several photos of the same object, the characteristic that has to be recognized is always the same. This is only possible after the features map is finished.
 • Flatten Layer symbolizes the artificial neural network's input layer. It is known as "Flattening" since it involves organizing an entity map into a column. This makes a big data vector suitable for the neural network's input possible.
• Max-Pooling Layer: The process of maxpooling is utilized to extract the most pertinent characteristics from the photos. In the original entity map, the final result is always the maximum value, and extraneous information are eliminated from each image to free up the network of neurons to do the task effectively

# This research proposes a CNN model for brain tumor segmentation from MRI images into two classes: tumor-containing and tumor-free. This experiment yielded an overall accuracy of 92% for the suggested model. In future work, the architecture of the proposed model could be perfected, and its reliability and performance will be evaluated with a large database.
