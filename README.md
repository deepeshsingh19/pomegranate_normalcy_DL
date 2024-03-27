## Project Title: Pomegranate Normalcy Detection using Deep Learning

### Introduction:
This project aims to classify images of pomegranates into two categories: "Normal" and "Abnormal" using deep learning techniques. The classification is based on the visual appearance of pomegranates, with the goal of detecting any abnormalities or defects in the fruit.

### Dataset:
The dataset consists of images of pomegranates, divided into a training set and a test set. The images are categorized into "Normal" and "Abnormal" classes. The training set contains 2405 images, while the test set contains 600 images.

### Model Architecture:
The Convolutional Neural Network (CNN) model used for classification consists of several convolutional layers followed by max-pooling, dropout, and batch normalization layers to extract features from the images. The final layers include fully connected layers with softmax activation for classification.

### Training and Evaluation:
The model was trained for 50 epochs using the Adam optimizer with a learning rate of 0.001. The training and validation accuracies and losses were monitored during training. After training, the model achieved a training accuracy of approximately 99.83% and a validation accuracy of approximately 97.50%.

### Model Evaluation:
The trained model was evaluated on the test dataset, achieving a test accuracy of approximately 97.50%. The number of trainable parameters in the model is 184,386.

### Inference:
Inference was performed on sample images from the test dataset, displaying both the actual and predicted labels along with confidence scores. Additionally, an option to upload custom images for prediction was provided.

### Conclusion:
The developed model demonstrates promising performance in classifying pomegranate images into "Normal" and "Abnormal" categories, with potential applications in quality control and fruit grading processes. Further improvements could be made by fine-tuning the model architecture and exploring additional data augmentation techniques.
