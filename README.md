The CNN trained for 5 epochs.

Each epoch shows:
accuracy → how well it learned the training data

loss → how wrong the model’s predictions are (smaller is better)

val_accuracy → how well it performs on unseen validation data

val_loss → error on validation data

Observation: Accuracy improves and loss decreases with each epoch → model is learning well.

In Test evaluation
After training, the model was tested on the test set, data it never saw before.
Test accuracy = 0.9897 → ~98.97% correct predictions
Loss = 0.0314 → very low, meaning confident predictions



 Keras CNN is successfully classifying MNIST digits with ~99% accuracy.

Everything setup (Python + VS Code + Keras/TensorFlow) is working correctly.
