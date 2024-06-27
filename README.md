# Leishmania Object Detection

This project implements an object detection model for Leishmania parasites using the Faster R-CNN architecture with a ResNet-50 backbone.
The dataset consists of images of Leishmania parasites and corresponding JSON labels for bounding boxes. The code includes data loading, training, evaluation, and visualization functionalities.

## Steps:
- Data Preparation: Load and preprocess images and annotations.
- Model Definition: Set up the Faster R-CNN model with a ResNet-50 backbone.
- Training: Train the model on the training dataset.
- Evaluation: Evaluate the model's performance on the test dataset using metrics such as Mean Average Precision (mAP), precision, recall, and F1 score.
- Hyperparameter Tuning: Use Optuna for hyperparameter optimization.
- Visualization: Visualize training loss and evaluation metrics over epochs, and detect Leishmania parasites in test images.

# Prerequisites
Before running the code make sure to get these libraries installed

```pip install torch torchvision pillow matplotlib scikit-learn optuna tensorflow tensorflow_ranking```

# Results
mAP score : 0.89
![image](https://github.com/xmonstabebex/object-detection/assets/89215956/a8643350-a442-4dd4-9c7d-0ffb3b398b4b)
