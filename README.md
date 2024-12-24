# Fruit-Classification
Image Classification Using AlexNet:
This project focuses on classifying images into one of 7 fruit categories using the AlexNet architecture.
About AlexNet:
AlexNet is a deep neural network architecture consisting of five convolutional layers and three fully connected layers. Some layers are followed by MaxPooling, and all use the ReLU activation function for faster and more effective training. The kernel sizes for the convolutional layers are 11x11, 5x5, 3x3, 3x3, and 3x3 respectively, making the network efficient in extracting features from images. The parameters were tuned based on training performance to ensure optimal results.
Steps and Purpose:
Exploratory Data Analysis (EDA): To understand the dataset by visualizing images, checking class distributions, and identifying potential anomalies.
This step ensures the dataset is clean and ready for training.
Model Definition (Using AlexNet Architecture): To define the AlexNet model with 5 convolutional layers (kernels: 11x11, 5x5, 3x3, 3x3, 3x3) followed by 3 fully connected layers.
This architecture is designed to extract hierarchical features, such as edges, textures, and high-level patterns, to effectively classify images.
Image Augmentation: To artificially expand the dataset by applying transformations like rotation, flipping, zooming, and shifting to images.
This improves the model's generalization by making it robust to variations in the images.
Callback Lists: To include tools like early stopping (to halt training when performance stops improving) and model checkpoints (to save the best version of the model during training).
These techniques prevent overfitting and save computation time.
Model Training: To train the model on the dataset using the backpropagation algorithm and optimize the weights through a gradient descent optimizer.
The training process is tuned for the best accuracy using hyperparameter optimization.
Learning Curves: To plot training and validation accuracy/loss curves to monitor the model's performance.
This helps identify underfitting, overfitting, or the need for further tuning.
Predictions on Sample Images: To test the trained model by predicting classes for unseen images and evaluating its performance.
This validates the practical utility of the model.
