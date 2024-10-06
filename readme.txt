Facial Emotion Recognition using GPU
This project performs facial emotion recognition using the February 2013 dataset. The model can detect and classify human emotions from facial expressions. 
The project is specifically designed to run on systems equipped with GPU acceleration for faster performance.

Requirements
To run this project, ensure that your system is set up with the following:

Python 3.10
This project requires Python version 3.10. It will not work with newer versions of Python.

CUDA v11.8 and cuDNN v8
The project is compatible with CUDA version 11.8 and cuDNN version 8. You can install these by following tutorials available on YouTube. Make sure to install them within a Conda environment, as this project was developed using Conda.

TensorFlow 2.10
The project is built using TensorFlow 2.10. Make sure you install this specific version, as newer versions may not be compatible with CUDA 11.8 and cuDNN v8.

Haar Cascade File
You will need to download the Haar Cascade file for face detection. It is freely available on the internet. The file typically looks like:
haarcascade_frontalface_default.xml

Installation Instructions:

1. Clone this repository:
git clone https://github.com/your-username/facial-emotion-recognition-using-gpu.git
cd facial-emotion-recognition-using-gpu

2. Set up the Conda environment: Make sure you have Conda installed on your system. Then, create and activate a new Conda environment with Python 3.10:
conda create --name facial-emotion-recognition python=3.10
conda activate facial-emotion-recognition

3. Install TensorFlow and other necessary libraries: 
Manually install TensorFlow 2.10 and any other libraries you need to run the project. You can install TensorFlow using:
pip install tensorflow==2.10

4. Install CUDA and cuDNN: Follow tutorials on YouTube to install CUDA v11.8 and cuDNN v8. Make sure these versions are installed, as the project is not compatible with newer versions of CUDA or cuDNN.

5. Download the Dataset: The dataset used for this project, FEB 2013, can be downloaded from Kaggle. Place the dataset in the appropriate directory after downloading.

6. Download the Haar Cascade file: Download the Haar Cascade file for face detection and place it in your project directory.


Running the Project :
Once everything is installed and set up, you can run the project using the following command:
python your_project_script.py

Ensure that your environment is properly set up with GPU support for TensorFlow 2.10.

Troubleshooting
Make sure you are using Python 3.10, CUDA v11.8, and cuDNN v8. Other versions will not work with this project.
If you run into any issues during the setup of CUDA and cuDNN, refer to YouTube tutorials on how to correctly install them in a Conda environment.


Libraries Used: 
TensorFlow 2.10
NumPy
OpenCV
Matplotlib


License
This project is licensed under the Database Contents License (DbCL) v1.0. Please see the LICENSE file for the full text of the license.