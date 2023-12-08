## Title: Mood Classification Using CNN
### A. Project Overview:
This project leverages Convolutional Neural Networks (CNNs) for mood classification based on facial expressions in images. By training a deep learning model on a labeled dataset containing happy and not happy images, the goal is to create an AI system that can recognize and categorize moods accurately.

### B. Project Structure: 
The project is organized into the following components:

#### 1] Data Exploration:
* The dataset contains images labeled with different moods, focusing on "happy" and "not happy" expressions.
* Images are loaded, visualized, and explored using OpenCV and Matplotlib.

#### 2] Data Preprocessing:
* Images are preprocessed using TensorFlow's ImageDataGenerator, including rescaling to normalize pixel values.
* The dataset is split into training and validation sets.

#### 3] Model Architecture:
* The CNN model is designed with convolutional layers followed by max-pooling layers to capture features in the input images.
* The final layers include fully connected layers for classification, producing a binary output (happy or not happy).

#### 4] Training and Evaluation:
* The model is trained on the training dataset and evaluated on a separate validation set.
* Key performance metrics such as accuracy are monitored during training.

#### 5] Testing:
* The model is tested on a set of unseen images to demonstrate its ability to classify moods in real-time.


## Visualizations

- **Load Sample Image:**

![App Screenshot](https://github.com/abhishekdeshmukh001/Mood-Classification-Using-CNN/blob/main/training/happy/2.jpg?raw=true)


- **Final Ouput (Classification):**

![App Screenshot](https://github.com/abhishekdeshmukh001/Mood-Classification-Using-CNN/blob/main/Output_Happy.png?raw=true)

![App Screenshot](https://github.com/abhishekdeshmukh001/Mood-Classification-Using-CNN/blob/main/Output_Not%20Happy.png?raw=true)


## - Future Improvements
* Discuss potential enhancements, like fine-tuning hyperparameters, increasing dataset diversity, or exploring more advanced CNN architectures.



## 🔗 Link
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhishek-sachin-deshmukh/)


## Authors

- [@abhishekdeshmukh001](https://github.com/abhishekdeshmukh001)
