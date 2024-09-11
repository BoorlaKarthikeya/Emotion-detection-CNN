
# Emotion Detection using CNN





## overview
This project focuses on real-time emotion detection using Convolutional Neural Networks (CNN) with advanced architectures. The model is trained on the FER 2013 dataset and deployed for live video streaming using OpenCV and radio. We tackle the challenge of class imbalance through image augmentation and class weights, improving the model's robustness. The final model based on ResNet50V2 achieved an overall accuracy of 66% in emotion classification across 7 emotional labels.


## Techstack
- Python
- TensorFlow
- VGG16
- ResNet50V2
- OpenCV
- Gradio
## Dataset
- FER 2013 Dataset: Contains labeled facial expressions across seven emotion categories. The dataset is highly imbalanced, requiring techniques like image augmentation and class weighting for better model training.
- [Dataset Link](https://www.kaggle.com/datasets/msambare/fer2013)
## Approach
1. ###  Preprocessing

- **Data Augmentation:** Used to balance the class distribution in the dataset.
- **Normalization:** Achieved a 93% accuracy rate.
- **Enhancements:** Images were resized and normalized to enhance model performance.
2. ### Model Development
- Designed and implemented custom CNN models.
- Explored advanced architectures such as VGG16 and ResNet50V2.
- **Final Model:** ResNet50V2-based model achieved 66% accuracy.
3. ### Model Evaluation
- Evaluated the model using precision, recall, and F1 score metrics.
- Targeted 7 emotion labels: Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral.
4. ### Results
- **Final Model Accuracy:** 66% on the test set.
- **Metrics:**
    - Precision, Recall, and F1 scores were calculated for all emotion categories.
## output
- **output1:**
   ![output1](output/output1.png)
- **output2:**
   ![output2](output/output2.png)
## Future Work

- Improve the model's accuracy using deeper architectures.
- Integrate more robust handling for class imbalance.
- Explore cross-dataset evaluations to generalize the model performance.
