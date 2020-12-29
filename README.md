# TrafficSignRecognition
## 1. Overview:
This group project explores basic machine learning models (MLP, RF and SVM) in classifying traffic signs. The dataset used for this project is GTRSB (German Traffic Sign Recognition Benchmark).

## 2. Result:
The model with the best performance is MLP(300) on HOG features on non-processed image with accuracy of 93% and F1 score of 92%

## 3. Content of the repository:
### 3.1 Data
* Includes train and test images in the dataset under .npy format. Images are separated into processed image and original images
* Due to file size restriction, the data for this project can be accessed through <shorturl.at/fjy68>

### 3.2 Notebook
Includes Jupyter notebook files of our 3 models (MLP, RF and SVM) trained on HoG features, SIFT+BoW features and on the images themselves

### 3.3 Sift features
### 3.4 HoG features
### 3.5 Model file
Includes the model with the best performance

### 3.5 Demo file
Run `python demo.py` to start the demonstration program. Upload a traffic sign and let the program predict the label

