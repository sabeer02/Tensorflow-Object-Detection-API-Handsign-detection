# TensorFlow Object Detection API - Handsign Detection

This project utilizes TensorFlow and the TensorFlow Object Detection API for detecting hand signs in images. The detection is powered by TensorFlow's deep learning capabilities and is enhanced with the use of OpenCV, labelimg.py for labeling, and Google Colab for collaborative development.

## Technologies Used

- **TensorFlow:** An open-source machine learning library developed by the Google Brain team. It is widely used for building and training machine learning models, including deep learning models.

- **TensorFlow Object Detection API:** A set of pre-trained models and tools for building object detection models using TensorFlow.

- **OpenCV:** An open-source computer vision and machine learning software library. It provides various functions and tools for image processing, including image loading, manipulation, and computer vision algorithms.

- **labelimg.py:** A graphical image annotation tool used for labeling objects in images. It generates XML files containing the object bounding box coordinates and class labels, which are often used in training object detection models.

- **Google Colab:** A cloud-based Jupyter notebook service provided by Google. It allows for free access to GPU and TPU resources, making it suitable for training machine learning models.

## Getting Started

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/sabeer02/Tensorflow-Object-Detection-API-Handsign-detection.git
   ```

2. **Install Dependencies:**
    ```bash
    pip install tensorflow opencv-python 
    ```
3. **Labeling Images:**

   Use labelimg.py to annotate your images with bounding boxes for handsigns. Save the labeled data in XML format.

4. **Training with TensorFlow Object Detection API:**

   Follow the TensorFlow Object Detection API documentation to train your model using the labeled data.

5. **Testing and Inference:**
   
   Use the trained model for handsign detection on new images or video streams. 
   You can also deploy the model to different platforms or integrate it into other applications.
   
## Notebooks and Google Colab

   Using Jupyter Notebook for Image collection and storing the generated images in the local directory
   The project includes Google Colab notebooks for collaborative development and training using Google's cloud resources. 
   Use these notebooks for training your model in a collaborative environment.

## Contributing
  
   If you would like to contribute to the project, feel free to fork the repository and submit pull requests. We welcome contributions and improvements to enhance handsign detection capabilities.
