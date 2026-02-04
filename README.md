# Fashion-MNIST-Image-Classification
## [Google Colab Link](https://colab.research.google.com/drive/1oJBe8a7f-ewO2ltAdmqbE9-JtvXsFpHU?usp=sharing)
## Questions:
### 1. What is the Fashion MNIST dataset?
#### Answer: The Fashion MNIST dataset is a collection of grayscale images of clothing items such as shirts, trousers, shoes, and bags. It contains 60,000 training images and 10,000 testing images, each with a size of 28×28 pixels. The dataset is commonly used as a benchmark for image classification tasks in machine learning.
### 2. Why do we normalize image pixel values before training?
#### Answer: Image pixel values are normalized to scale them between 0 and 1, which helps the neural network train more efficiently. Normalization speeds up convergence, improves numerical stability, and prevents large pixel values from dominating the learning process.
### 3. List the layers used in the neural network and their functions.
#### Answer: Flatten layer – Converts the 28×28 image into a one-dimensional array so it can be processed by dense layers.
#### Dense (hidden) layers – Learn patterns and features from the input data using weighted connections and activation functions.
#### ReLU activation – Introduces non-linearity, allowing the model to learn complex patterns.
#### Dense output layer – Produces raw scores (logits) for each of the 10 clothing classes.
### 4. What does an epoch mean in model training?
#### Answer: An epoch refers to one complete pass of the entire training dataset through the neural network. Multiple epochs allow the model to learn and improve its parameters gradually.
### 5. Compare the predicted label and actual label for the first test image.
#### Answer: The predicted label for the first test image matches the actual label, indicating that the model correctly classified the image. This shows that the trained model can accurately recognize clothing items from unseen data.
### 6. What could be done to improve the model’s accuracy?
#### Answer: The model’s accuracy can be improved by increasing the number of neurons, adding additional hidden layers, increasing the number of training epochs, and applying techniques such as Batch Normalization and Dropout to reduce overfitting and improve generalization.
