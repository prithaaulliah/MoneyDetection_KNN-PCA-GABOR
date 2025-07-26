In this project, I performed a money detection experiment. 

In this banknote image detection, I used machine learning methods: KNN, PCA, and GABOR.
Here's an explanation of the three methods:
1. PCA (Principal Component Analysis)
PCA is a dimensionality reduction technique used to reduce the number of features (variables) in a dataset while retaining important information. In short, it calculates variance in the dataset and projects the data onto a direction. It's used to reduce data complexity, speed up processing, and reduce overfitting.

2. Gabor Filter
Gabor is a feature extraction method commonly used in image processing.
Its function is to capture texture and edge information in an image using a sinusoidal filter with a Gaussian function.

3. KNN (K-Nearest Neighbors)
KNN is a distance-based classification (or regression) algorithm.
In short, determine the parameter k (the number of nearest neighbors). Calculate the distance between the test data and the training data (usually the Euclidean distance). Take the k nearest neighbors and select the class with the largest number of neighbors.

Gabor → Feature extraction from images (e.g., texture).
PCA → Dimensionality reduction to minimize the number of Gabor features.
KNN → Image classification based on extracted and reduced features.

The following is the distribution of the dataset used
<img width="803" height="667" alt="image" src="https://github.com/user-attachments/assets/4f629c1a-ac58-42b8-a7a6-c5800da4fef3" />

The following are the results of implementing the following method:
1. KNN
   Confusion Matrix:
   <img width="888" height="824" alt="image" src="https://github.com/user-attachments/assets/2ee0bd97-8dfb-4ece-aba5-9fb0ccc3513b" />
   ROC Curve:
   <img width="702" height="547" alt="image" src="https://github.com/user-attachments/assets/5917bb0b-0fde-46e0-98cc-075a23baae43" />
   Evaluation:
   <img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/1e4af1d7-8b94-4355-a916-cc0343066cea" />

2. KNN+GABOR
   Confusion Matrix:
   <img width="888" height="824" alt="image" src="https://github.com/user-attachments/assets/efc8fdfe-8a8a-4e9c-9ed2-23e3dd06351d" />
   ROC curve:
   <img width="857" height="701" alt="image" src="https://github.com/user-attachments/assets/b620783a-06ac-49e1-8870-87fb1aeac71b" />
   Evaluation:
   <img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/e032e856-61a0-4c35-b236-e1f879a57661" />

3. KNN+PCA
   Confusion Matrix:
   <img width="888" height="824" alt="image" src="https://github.com/user-attachments/assets/c1c25bf4-c6cd-4857-a7e7-0152a5e1e787" />
   ROC Curve:
   <img width="702" height="547" alt="image" src="https://github.com/user-attachments/assets/423bf3ee-3c73-4815-b395-4f4a478acb9a" />
   Evaluation:
   <img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/37b78ccd-350e-4e93-9472-a28031c8aae4" />

4. KNN + GABOR + PCA
   Confusion Matrix:
   <img width="888" height="824" alt="image" src="https://github.com/user-attachments/assets/1f1ff2af-3a23-4a74-8b55-962b4e2c1820" />
   ROC Curve:
   <img width="857" height="701" alt="image" src="https://github.com/user-attachments/assets/478faedc-4e6b-4021-8388-6c6a0354da0e" />
   Evaluation:
   <img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/2def397f-58e7-4209-9f58-60f1281fdc56" />

   The following is a comparison of the results of the 4 method implementations:
   <img width="989" height="790" alt="image" src="https://github.com/user-attachments/assets/c25b61b8-db0e-47ae-9de4-0d34e636157e" />


   





   

   


