# Classification_Project_of_Sports_Celebrities

## Hey there, sports fans! ⚽🎾🏏
Welcome to our super cool project, the Sports Celebrity Classification Project. This is where we're using the magic of machine learning to classify images of your favorite sports celebrities.

## What's it all about? 🤔
We've got a dataset that's packed with images of five sports celebrities - Ms Dhoni, Roger Federer, Ronaldo, Lionel Messi, and Virat Kohli. We've used a chrome extension to bulk download these images, because who has time to download images one by one, right?

## How does it work? 🛠️
We've used NumPy and OpenCV haarcascades for data cleaning and preprocessing. We've also performed a wavelet transformation on the images and then stacked both the cropped and the wavelet transformed image into a new image directory. Sounds cool, huh?

For the model training, we've used Scikit Learn. We've also used GridSearchCV to predict the best set of parameters for the model. We've tried out a few ML models - SVM, Logistic Regression, and Random Forest.

## And the results? 📊
We've managed to achieve an accuracy of 78% with just 126 images. Not too shabby, right?

## Libraries we've used 📚
- Numpy
- OpenCV
- Shutil
- Pywavelet
- Joblib
- Json

So, that's about it! Feel free to explore the project and let us know what you think. Happy coding! 🚀
