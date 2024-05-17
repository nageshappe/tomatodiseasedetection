1. Introduction
Tomato fruit diseases can significantly impact crop yield and quality. Early and accurate detection is crucial for effective disease management.
This project utilizes transfer learning and ensemble modeling to build a powerful disease detection system, combining the strengths of multiple pre-trained CNN models.

2. Features
Transfer Learning: Utilizes pre-trained CNN models for feature extraction.
Ensemble Model: Combines multiple models to improve accuracy and robustness.

3. Requirements
   Python 3.6 or higher
   TensorFlow 2.x
   Keras
   OpenCV
   NumPy
   Pandas
   Scikit-learn
   Matplotlib

   4. Installation
   Clone the repository:
   git clone https://github.com/yourusername/tomatodiseasedetection.git

   
   5. pip install -r requirements.txt

    6. Usage
    7. Prepare Dataset:
        Ensure you have a dataset of tomato fruit images categorized by disease type.
       The dataset should be organized in subdirectories, each named after the corresponding disease.
       Train the Model:
         Evaluate the Model:
          Detect Diseases:
   8. Model Architecture
      The ensemble model consists of several pre-trained CNNs,such as:
      VGG16
      ResNet50
      InceptionV3
      DenseNet121
      Xception

      These models are fine-tuned on the tomato fruit disease dataset and combined to form an ensemble for improved performance.
   9. Dataset
      The dataset used for this project should contain labeled images of tomato fruits affected by various diseases.
      Each category should represent a specific disease.
    10. Training
      The training process involves:
        Loading and preprocessing the dataset.
       Fine-tuning pre-trained models using transfer learning.
       Combining the models into an ensemble.
        Training the ensemble model on the dataset.
   11. Evaluation
       The model is evaluated using standard metrics such as accuracy, precision, recall, and F1-score.
       Confusion matrices and ROC curves are also generated for detailed analysis.
   12. Results
   13. The ensemble model achieves high accuracy in detecting tomato fruit diseases, outperforming individual models.
       Detailed results and performance metrics are:
       Accuracy: 98.54%
       Accuracy: 95%Precision: 94%Recall: 93%
