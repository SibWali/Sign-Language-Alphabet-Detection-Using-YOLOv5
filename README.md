# Sign-Language-Alphabet-Detection-Using-YOLOv5

This project detects American Sign Language (ASL) alphabet signs using a deep learning model (YOLOv5). It is built using Python and trained on a dataset of hand signs.
you can access this ipynb file by clicking the rlease tag here you can download that file 

📌 What This Project Does
Downloads the American Sign Language Letters dataset using Roboflow

Uses YOLOv5 to detect ASL alphabet signs in images

Trains a model on labeled image data

Tests and shows prediction results on custom images

🔧 Tools & Libraries Used
Python (Google Colab)

YOLOv5 – for object detection

Roboflow – to get the dataset

OpenCV – for working with images

IPython Display – for visual output in Colab

📁 Steps in the Notebook
Setup & Install Dependencies

Install Ultralytics YOLOv5

Install Roboflow and set API key

Download Dataset from Roboflow

Dataset: American Sign Language Letters

Automatically downloads YOLOv5-compatible format

Modify data.yaml File

Fix paths to train/images, valid/images, etc.

Train YOLOv5 Model

Use the dataset to train a YOLOv5 model on ASL images

Test with Sample Image

Upload a custom image

Run model to detect the alphabet shown in the image

🧪 How to Test the Model
Upload an image of a hand showing an ASL letter.

Run the prediction cell in the notebook.

The detected letter will be displayed with a bounding box.

📷 Sample Output
Input: Hand image with sign

Output: Bounding box with predicted letter label

