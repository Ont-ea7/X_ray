#Approach
Used deep learning (CNN) for image classification.
Preprocessed the dataset by:
Resizing images
Normalizing pixel values
Split the dataset into:
Training set
Validation set
Test set
Built a CNN model with:
Convolutional layers
Pooling layers
Fully connected (Dense) layers
Applied activation functions like ReLU and Softmax.

#Methodology :Data Preprocessing
Loaded dataset from directory
Converted images into arrays
Resized images to fixed dimensions
Normalized pixel values (0–1 range)

Model Building
Designed CNN architecture:
Conv2D → MaxPooling → Dropout
Flatten → Dense layers
Used:
Loss function: categorical_crossentropy (or binary_crossentropy)
Optimizer: Adam
Training:
Trained model on training dataset
Validated performance using validation set
Tuned hyperparameters (epochs, batch size)
Evaluation:
Tested model on unseen test data
Evaluated using:
Accuracy
Loss
Confusion Matrix (optional)
#Findings
The CNN model successfully learned features from X-ray images.
Achieved good accuracy on training and validation datasets.
Model performance depends on:
Dataset size
Image quality
Hyperparameter tuning
Overfitting can occur if the model is too complex or dataset is small.
