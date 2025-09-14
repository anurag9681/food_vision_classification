# Food Vision Big™ - Milestone Project

**Author:** Anurag Yadav
**Source:** [Zero to Mastery TensorFlow Deep Learning - Food Vision Big™ Project](https://dev.mrdbourke.com/tensorflow-deep-learning/07_food_vision_milestone_project_1/)

## 📚 Project Overview
This project is part of the "Zero to Mastery TensorFlow for Deep Learning" course by Mr. Daniel Bourke. It builds on the previous Food Vision mini project by scaling up to the full Food101 dataset. The goal is to train a deep learning model that can classify food images into 101 different categories with high accuracy, aiming to beat the top-1 accuracy of 77.4% from the DeepFood paper.

## 🍽️ Dataset
The project uses the [Food101 dataset](https://www.tensorflow.org/datasets/catalog/food101), which consists of:
- **75,750 training images**
- **25,250 testing images**
- 101 different food categories

## 🧠 Model Architecture
The project employs the EfficientNetB0 convolutional neural network as the base model for feature extraction, known for its efficiency and accuracy in image classification tasks.

## ⚙️ Key Features and Techniques
- **Mixed Precision Training:** Speeds up training and reduces memory usage.
- **Data Prefetching:** Optimizes data loading during training.
- **Fine-Tuning:** Improves model performance by unfreezing some layers.
- **Evaluation:** Confusion matrix, F1-score graphs, and prediction visualizations.

## 🚀 How to Run the Project
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/food-vision-big.git
