# Pneumonia Classifier Using Chest XRay
In this notebook, we perform a binary classification on chest X-ray images to determine whether a person has healthy lungs or is diagnosed with pneumonia. 
The dataset used is the "Chest X-ray Images (Pneumonia)" dataset from Kaggle. 
We combined both viral and bacterial pneumonia into a single class. 
For this classification, we used a custom deep convolutional neural network (CNN) model and achieved an accuracy of 95% on the test set.

![chest-xray](https://github.com/user-attachments/assets/a87056e1-0a55-4117-ad48-bdb5fd810459)


# Libraries and Dependencies
This project requires the following libraries to run. You can install them using the following commands.

For PyTorch and Torchvision:

If you want to use GPU with CUDA support, install PyTorch and Torchvision with the following command:

```shell
pip install torch torchvision torchmetrics --index-url https://download.pytorch.org/whl/cu118
```

For CPU-only installation (if you do not have a compatible GPU), use this command:

```shell
pip install torch torchvision torchmetrics
```

For Other Dependencies:
To install the other required libraries, use the following command:

```shell bash
pip install matplotlib scikit-learn Pillow 
```

Make sure to install the correct version of PyTorch based on your hardware and CUDA configuration.


