### Define a CNN classifier as a Sequential model with the following layers:
- Convolution layer with 32 filters, kernel size 3 and stride 1, followed by a rectilinear unit (relu) activation.
- Convolution layer with 16 filters, kernel size 3 and stride 1, followed by a rectilinear unit (relu) activation.
- Flatten layer.
- Dense layer with the appropriate number of units and activation function.
### Train your CNN on the given train_images using a suitable optimizer.
- Only run your training loop for a single epoch to keep the run time down.
- Use accuracy as a metric, and an appropriate loss function.
### Evaluate your CNN on the given test_images:
- Calculate the accuracy of your trained classifier on the test_images, storing your answer in the variable test_accuracy.
- The above instructions are what you will need to use to submit the project, but once you've passed the project, feel free to experiment with the model architecture and training arguments to achieve a better accuracy!