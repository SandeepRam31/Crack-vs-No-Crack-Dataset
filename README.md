# Crack-vs-No-Crack-Dataset

### How to use this:
* Run "pip install -r requirements.txt"
* Go inside code files and open gradcam.py
* Uncomment one of the 3 lines at the bottom of the file to predict on image, get highlights or predict on directory

### Summary
I have used a convolutional neural network to classify between crack and no crack images. The model has 5000+ parameters, hence trains really fast. 
I have also implemented Grad Cam, which allows us to visualize the place in the image where the crack is present.

Model:
![image](https://user-images.githubusercontent.com/55907397/137615699-83ad3a28-79e4-4923-8426-1a37544c65a5.png)
