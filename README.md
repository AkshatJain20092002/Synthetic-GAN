# Synthetic GAN

## Project Overview

This study explores around the impact of using the Deep Convoluted Generative Adversarial Networks (DCGANs) to tackle the problem of class imbalance in image related data, furthermore, using the DCGAN to improve the performance of deep neural network models for classification. Class imbalance in image dataset has been a severe problem and leads to significant challenge for deep learning model's performance. Using the introduction of imbalance within the dataset, GAN models can generate and utilize synthetic data. The study looks on how using the integrated GAN-generated images can affect the performance of model and focusing on improving and enhancing the overall accuracy of model classification by resolving imbalancing. Results prove that GAN-based data augmentation influences the model training and classification outcomes, showing potential benefits of using GANs for handling the imbalance data in machine learning models.

## Results

### TABLE I : MODEL PERFORMANCE METRICS WITHOUT GAN GENERATED IMAGES

| Model       | Accuracy | Loss   | Precision | Recall | F1 Score |
|-------------|----------|--------|-----------|--------|----------|
| InceptionV3 | 0.75     | 0.2185 | 0.76      | 0.75   | 0.75     |
| MobileNet   | 0.65     | 0.1496 | 0.69      | 0.65   | 0.65     |
| ResNet50    | 0.58     | 0.2214 | 0.69      | 0.58   | 0.57     |
| VGG16       | 0.22     | 1.6079 | 0.05      | 0.22   | 0.08     |

### TABLE II : MODEL PERFORMANCE METRICS WITH GAN GENERATED IMAGES

| Model       | Accuracy | Loss   | Precision | Recall | F1 Score |
|-------------|----------|--------|-----------|--------|----------|
| InceptionV3 | 0.89     | 0.3098 | 0.90      | 0.90   | 0.89     |
| MobileNet   | 0.82     | 0.109  | 0.85      | 0.82   | 0.82     |
| ResNet50    | 0.71     | 0.459  | 0.78      | 0.71   | 0.70     |
| VGG16       | 0.24     | 1.5823 | 0.05      | 0.23   | 0.07     |

