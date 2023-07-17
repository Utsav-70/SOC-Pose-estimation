# SOC-Pose-estimation
**Introduction**

Human pose estimation aims to accurately estimate the positions of body joints or keypoints, such as the shoulders, elbows, wrists, hips, knees, and ankles. It involves predicting the x and y coordinates of these keypoints in an image or video frame. This repository provides a collection of state-of-the-art models, algorithms, and tools for performing human pose estimation tasks.

**Usage**

The human pose estimation models provided in this repository can be used to estimate human poses from images or videos. The usage instructions may vary depending on the specific model. Generally, the following steps are involved:

Load the pre-trained model weights.

Preprocess the input image or video frame by resizing, normalizing, or applying any required transformations.

Pass the preprocessed input through the pose estimation model to obtain the keypoints' predictions.

Visualize the predicted keypoints on the input image or video frame.

**Models**

This repository includes various human pose estimation models, such as:

Regression-based pose estimator: Implements a regression-based approach to estimate the keypoints' coordinates directly.

Convolutional Neural Network (CNN) pose estimator: Utilizes a CNN architecture to detect and localize keypoints in images or video frames.

DeepPose cascade regressor: Implements a DNN-based cascade regressor using Deeppose to estimate human poses

**Data**

To train and evaluate the human pose estimation models, the following datasets are used:

Mnist: Contains handwritten digit images for training a CNN-based pose estimator.

CIFAR-10: Provides a dataset of various object images for implementing a CNN to predict human poses.

Fashion MNIST: A dataset of fashion item images used to train a classification model for human pose estimation.

Stackhour Glass: Consists of images of glasses to apply the ResNet50 model for classifying Pokemons.
