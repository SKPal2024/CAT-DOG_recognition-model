🐱🐶 Cat vs Dog Recognition using TensorFlow
Overview

This project implements an image classification model that distinguishes between cats and dogs using TensorFlow and Keras. The model is built using a fully connected neural network with three hidden layers, employing ReLU activation for hidden layers and a Sigmoid activation function for the output layer.

The model achieves an accuracy of approximately 80% on the validation dataset.

| Layer | Type         | Filters/Units | Activation | Purpose                   |
| ----- | ------------ | ------------- | ---------- | ------------------------- |
| 1     | Rescaling    | -             | -          | Normalize pixel values    |
| 2     | Conv2D       | 32            | ReLU       | Feature extraction        |
| 3     | MaxPooling2D | -             | -          | Downsampling              |
| 4     | Conv2D       | 64            | ReLU       | Deeper feature extraction |
| 5     | MaxPooling2D | -             | -          | Downsampling              |
| 6     | Conv2D       | 128           | ReLU       | High-level features       |
| 7     | MaxPooling2D | -             | -          | Downsampling              |
| 8     | Flatten      | -             | -          | Convert to 1D vector      |
| 9     | Dense        | 128           | ReLU       | Fully connected layer     |
| 10    | Dense        | 1             | Sigmoid    | Binary classification     |

⭐🌟 Add your own dataset. It can be found on online cat dog dataset  https://www.kaggle.com/datasets/bhavikjikadara/dog-and-cat-classification-dataset


how this works
<img width="2880" height="1704" alt="1" src="https://github.com/user-attachments/assets/f441e16f-f456-4141-90b6-5c04b72e3d12" />

<img width="2880" height="1704" alt="2" src="https://github.com/user-attachments/assets/92984dbb-e380-4890-9930-27d8711cd34f" />

