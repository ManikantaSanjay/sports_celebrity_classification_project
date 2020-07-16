# classification_project
This project deals with classification of sports celebrities containing 5 classes(celebrities) based on the image.I was able to achieve a accuracy of 78% with just 126 images.
I have created my own dataset by using chrome extension for bulk downloading of images.I have used NumPy and OpenCv haarcascades for data cleaning and data preprocessing.Then,I have done Wavelet Transformations for the images and vertically stacked both the cropped and the wavelet transformed image into a image directory.
Later,For Model training i have used Scikit Learn and GridSearchCV has been used for predicting the best set of parameters for the model and have checked for SVM,Logistic regression,and Random Forest.
Libraries Used:
i>Numpy
ii>OpenCV
iii>Shutil
iv>Pywavelet
v>Joblib
vi>Json
