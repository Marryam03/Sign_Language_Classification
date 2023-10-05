# Sign_Language_Classification
This project develops a Convolutional Neural Network (CNN) model to recognize sign language gestures. The model was trained on the Sign Language MNIST dataset, which consists of hand gestures representing letters of the alphabet.
I implemented a CNN model using TensorFlow and Keras for sign language recognition. The accuracy achieved on the test dataset reflects the model's ability to understand and classify hand gestures representing letters of the alphabet.

1) Data Preparation: The Sign Language MNIST dataset is loaded and preprocessed. Images are normalized to a range of [0, 1].

2) Data Visualization: The code includes visualizations to explore the dataset, such as class distribution and sample images.

3) Data Augmentation: Image data augmentation is applied to improve model generalization. Techniques like rotation and shifting are used to create variations of the training images.

4) Model Architecture: The CNN model consists of multiple convolutional layers with batch normalization, max-pooling, and dropout layers to prevent overfitting. It ends with a softmax layer for 25 class predictions (A-Z letters).

5) Model Training: The model is trained using the augmented training data, and the training process is monitored using a custom callback that stops training when a specified accuracy threshold is reached.

6) Evaluation: The trained model is evaluated on the test dataset, and accuracy metrics are printed.

7) Confusion Matrix: A confusion matrix is generated to visualize the model's performance in classifying each sign language gesture.

8) Sample Prediction: A sample image from the test dataset is displayed with the model's predicted letter and the true label.
