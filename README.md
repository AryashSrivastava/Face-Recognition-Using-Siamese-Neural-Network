# Face-Recognition-Using-Siamese-Neural-Network
Real-time facial recognition app using Siamese Neural Networks with TensorFlow. Hands-on learning of advanced NN concepts, CNNs, and custom layers. Build efficient data pipelines. Perfect for those keen on AI and image processing.

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```
<img width="657" alt="Screenshot 2024-05-19 at 8 11 30 AM" src="https://github.com/AryashSrivastava/Face-Recognition-Using-Siamese-Neural-Network/assets/145992546/39ac72bd-2a27-4a8f-8b3b-7f88f785e6d8">


## Getting Started


### Installation and Setup
Installing Dependencies and Preparing Data: Begin by installing necessary libraries and acquiring training images. This step ensures that the project has access to essential resources.

* Setting up File Operations: Utilize OS libraries to perform file operations, facilitating the creation and organization of folders within the local desktop environment. This step streamlines the management of project files and directories.

### Data Acquisition and Preprocessing
Facial Image Capture with OpenCV: Employ OpenCV for capturing real facial images. This process involves utilizing the camera to gather authentic data for training and testing purposes.

* Data Augmentation for Error Minimization: Implement data augmentation techniques to generate and store distorted images. By diversifying the dataset, potential errors during the learning process are mitigated, enhancing model robustness.

* Image Preprocessing and Labeling: Conduct preprocessing tasks such as resizing, normalization, and pairing of positive and negative images with corresponding labels (0 for negative, 1 for positive). This ensures data consistency and prepares the dataset for model training.

### Model Development and Training
Building the Siamese Neural Network: Construct the Siamese neural network architecture comprising eight layers. This includes four convolutional layers (CNN), three max-pooling layers, and dense hidden layers. Additionally, incorporate a custom distance layer to quantify image similarity. Train the Siamese model to learn distinctive features from paired images.


<img width="687" alt="Screenshot 2024-05-19 at 8 13 11 AM" src="https://github.com/AryashSrivastava/Face-Recognition-Using-Siamese-Neural-Network/assets/145992546/8273f662-530b-4ee5-86bb-ecf01df3c24b">


### Integration and Deployment
Incorporating Real-Time Face Recognition: Utilize OpenCV and OS libraries for storing captured real-time facial images as input for prediction and identification. This integration enables seamless interaction with the user and enhances the practicality of the application.

Defining Verification Criteria: Establish a verification model with predetermined detection and validation thresholds. These thresholds serve as criteria for determining the acceptable distance between images, ensuring accurate facial recognition results.

### Evaluation and Results
Real-Time Face Recognition: Demonstrate the efficacy of the developed system through real-time face camera detection. Showcase the capability of the application to accurately identify and distinguish faces in varying environments.





## Built With

* [TensorFlow](https://www.tensorflow.org/) - Deep Learning framework used
* [OpenCV](https://opencv.org/) - Library for computer vision tasks





## Author

* **Aryash Sriastava** - *Initial work* - [https://github.com/AryashSrivastava]




## Acknowledgments


* I extend my sincere gratitude to my mentors for their invaluable guidance and support throughout the duration of this project. Their expertise and encouragement have been instrumental in shaping its success.

* I am deeply thankful to the Analytics Club of IIT Bombay for organizing WIDS (Winter in Data Science). Participating in this event proved to be immensely beneficial, as it provided me with valuable insights and opportunities to enhance my skills in the field of Computer Vision.

