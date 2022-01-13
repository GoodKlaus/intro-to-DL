# 1. Convolutions and Poolings
- Convolutional layer is a special case of a fully-connected layer.
- Convolutional layer works the same way for every input patch.
- Pooling layer can reduce spatial dimensions (width and height of the input volume).
- Pooling layer provides translation invariance.
- Back-propagation for convolutional layer first calculates the gradients as if the kernel parameters were not shared and then takes a sum of gradients for each shared parameter.
