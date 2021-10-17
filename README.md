# Crack-vs-No-Crack-Dataset

### How to use this
* Run "pip install -r requirements.txt"
* Go inside code files and open gradcam.py
* Uncomment one of the 4 lines at the bottom of the file to predict on image, get highlights, predict on directory or get the area that has been cracked

### Summary
I have used a convolutional neural network to classify between crack and no crack images. The model has 5000+ parameters, hence trains really fast. 
I have also implemented Grad Cam, which allows us to visualize the place in the image where the crack is present.
The trainied model is saved in a folder called "neural network", inside the code_files directory. Please do not delete or make changes to this file

### Model Summary


![image](https://user-images.githubusercontent.com/55907397/137615699-83ad3a28-79e4-4923-8426-1a37544c65a5.png)


### Model Architecture

![image](https://user-images.githubusercontent.com/55907397/137615769-1fb04f55-9e0a-4ff5-ba29-69768093ad41.png)

### Model Output

![image](https://user-images.githubusercontent.com/55907397/137617556-ef634766-f518-4d1f-a774-eb99fefaf07c.png)


Feel free to create a new branch to add files or make changes to this repository
