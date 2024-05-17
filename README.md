<h2>1. Introduction:</h2><br>
Tomato fruit diseases can significantly impact crop yield and quality. Early and accurate detection is crucial for effective disease management.<br>
This project utilizes transfer learning and ensemble modeling to build a powerful disease detection system, combining the strengths of multiple pre-trained CNN models.
<p>
<h2>2. Features:-</h2>
Transfer Learning: Utilizes pre-trained CNN models for feature extraction.
Ensemble Model: Combines multiple models to improve accuracy and robustness.

<h2>3. Requirements:-</h2>
<ul>
   <li>Python 3.6 or higher</li>
<li>TensorFlow 2.x</li>
   <li>Keras</li>
   <li>OpenCV</li>
   <li>NumPy</li>
   <li>Pandas</li>
   <li>Scikit-learn</li>
   <li>Matplotlib
</li>
</ul>
<p></p>   
   <h2>4. Installation:-</h2>
   Clone the repository:
   git clone https://github.com/nageshappe/TomatoDiseaseDetection.git

   <p></p>
   <h2>5. pip install -r requirements.txt</h2>

   <p></p>
    <h2>6. Prepare Dataset:</h2>
        Ensure you have a dataset of tomato fruit images categorized by disease type.
       The dataset should be organized in subdirectories, each named after the corresponding disease.
   <h2>7. Model Architecture:-</h2>
      The ensemble model consists of several pre-trained CNNs,such as:
     <ul>
   <li>VGG16</li>
<li>ResNet150</li>
   <li>InceptionV3</li>
   <li>DenseNet121</li>
   <li>Xception</li>
   
</ul>
   
      These models are fine-tuned on the tomato fruit disease dataset and combined to form an ensemble for improved performance.
   <h2>8. Dataset:-</h2>
      The dataset used for this project should contain labeled images of tomato fruits affected by various diseases.
      Each category should represent a specific disease.
    <h2>9. Training:-</h2>
      The training process involves:
        Loading and preprocessing the dataset.
       Fine-tuning pre-trained models using transfer learning.
       Combining the models into an ensemble.
        Training the ensemble model on the dataset.
   <h2>10. Evaluation:-</h2>
       The model is evaluated using standard metrics such as accuracy, precision, recall, and F1-score.
       Confusion matrices and ROC curves are also generated for detailed analysis.
   <h2>11. Results:-</h2>
       The ensemble model achieves high accuracy in detecting tomato fruit diseases, outperforming individual models.
       Detailed results and performance metrics are:
       <b>Accuracy: 98.54%
       
