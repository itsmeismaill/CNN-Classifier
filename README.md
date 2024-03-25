Objective : The main purpose behind this lab is to get familiar with Pytorch library, to build
neural architectures, CNN, RCNN, FCNN, Vit, etc for computer vision.

###  Comparison of CNN Classifier and Vision Transformer (ViT) on MNIST Dataset

#### Part 1: CNN Classifier
1. **Architecture and Training**:
   - Constructed a CNN architecture using PyTorch, incorporating convolutional layers, pooling layers, and fully connected layers.
   - Defined hyperparameters such as kernel size, padding, stride, and optimizer (e.g., Adam) for training.
   - Leveraged GPU mode for faster training and inference.

2. **Evaluation and Comparison**:
   - Utilized the CNN classifier to classify the MNIST dataset.
   - Compared performance metrics (accuracy, F1 score, loss, training time) between the CNN classifier and Faster R-CNN.

3. **Fine-Tuning with Pretrained Models**:
   - Fine-tuned pretrained VGG16 and AlexNet models on the MNIST dataset.
   - Evaluated the fine-tuned models against the CNN classifier and Faster R-CNN.

#### Part 2: Vision Transformer (ViT)
1. **Building ViT Model**:
   - Followed a tutorial to implement a Vision Transformer (ViT) from scratch using PyTorch.
   - Adapted the ViT architecture for image classification on the MNIST dataset.

### Conclusion:
- **Model Performance**: Evaluated multiple models (CNN, Faster R-CNN, ViT) on the MNIST dataset, considering various metrics.
- **Comparative Analysis**: Explored strengths and weaknesses of each model, highlighting differences in performance and computational requirements.
- **Insights and Recommendations**: Provided insights into the suitability of each model for different computer vision tasks and recommended potential use cases based on the findings.

