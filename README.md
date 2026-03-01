# MobileNetV2_Transfer_Learning - Birds vs. Insects Image Classifier

First of all, this project implements a custom image classifier using transfer learning with the MobileNetV2 pre-trained model to distinguish between images of birds (sourced from the Tiny Bird Species Dataset) and insects (supplemented from public datasets). Developed using TensorFlow and Keras, the solution incorporates data augmentation, fine-tuning, and comprehensive evaluation metrics.

# Objectives
- Build a binary image classifier for birds vs. insects using a small custom dataset.
- Apply transfer learning with MobileNetV2 and fine-tune the model.
- Utilize data augmentation to improve robustness.
- Evaluate model performance with training logs, accuracy, and a confusion matrix.

# Code Structure
  - *Data Loading*: Uses ImageDataGenerator for augmented data flow.
  - *Model*: MobileNetV2 with a custom top layer, fine-tuned on last 20 layers.
  - *Training*: Two-phase training with Adam optimizer.
  - *Evaluation*: Generates logs, plots, and metrics.

# Results
- *Accuracy*
- *Training Logs*
- *Confusion Matrix*

In conclusion, the birds versus insects classifier successfully demonstrated the power of transfer learning on a small custom dataset. With a test accuracy exceeding 85-90%, the model showcased the effectiveness of data augmentation and fine-tuning in handling natural image variability. Executed on Google Colab with GPU support, this project highlighted proficiency in TensorFlow/Keras, data preprocessing, and model evaluation, laying a foundation for future advanced machine learning applications in wildlife classification.

MIT License 
Copyright (c) 2025 *1453nicat*
