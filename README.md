# Image_Classification_using_CNN
## Adout Project
In this deep learning project,we classify images of the following sports persons:

1. Virat kohli
2. Serena Williams
3. Roger Federer
4. Maria Sharapova
5. Lionel Messi

## Libraries Used
Numpy
Matplotlib
cv2
Tensorflow
scikit-learn
tqdm
PIL


#### Model Chosen
The Neural Network Architecture used for this image classification is Convolutional Neural Network(CNN) implemented using TensorFlow and Keras. The architecture includes convolutional layers for feature extraction, max-pooling layers for down-sampling, a flatten layer to convert the 2D feature maps to a vector, and densely connected layers for classification.

#### Training Process
The training process, including data loading, preprocessing, and model training, is well-structured.The model is trained for 50 epochs with a batch size of 32.The training set is further split into training and validation sets using a 70-30 split.During training, the script uses the ModelCheckpoint callback to save the best model based on validation accuracy and the EarlyStopping callback to stop training if validation accuracy does not improve for three consecutive epochs.

#### Critical Findings
The script prints the accuracy achieved by the model on the test set after training, providing an overall performance metric.A classification report is generated, which includes precision, recall, F1-score, and support for each class, giving detailed insights into the model's performance on individual classes.A single image is loaded and preprocessed for prediction, demonstrating how the model can be used for real-world predictions.
