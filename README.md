# FACIAL-KEYPOINT-DETECTION
Facial Keypoint detection is an important application in computer vision. This particular application has its contribution in many other applications such as face recognition, drowsiness detection, facial expression anlysis, 3D face modelling and most importantly in filters like snapchat filters.

This particular project detects 15 key-points in a face using CNN model and data-augmentation techniques which hepled in increasing the dataset and at the same time to get images with various transformations.

### **Data Augmentation Techniques Applied**
1. Horizontal Flipping.
2. Rotation Augmentation.
3. Brightness Alteration.
4. Horizontal and Vertical Shift.
5. Adding Random Noise.

### **CNN Model**
1. A 12-layer CNN architecture is used followed by 2 fully connected layers.
2. Leaked ReLu activations in convolutional layers.
3. Relu activation in first dense layer.
4. Linear activation in second dense layer.
5. Each convolutional layer is followed by batch normalization and max-pooling.
6. A dropout layer is also added between the dense layers.
7. Output layer consists of 30 units, resembling x and y coordinates of 15 key-points.

Metrics used are mean absolute error and accuracy.

