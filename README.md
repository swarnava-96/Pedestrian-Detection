# Pedestrian-Detection

### Goal: The goal of this mini project is to detect Pedestrians in a street recorded from a cctv footage using OpenCV and Haarcascade Classifier

### Brief Description:
I have used OpenCV and Haarcascade classifier in this project. 


So, what is Haar Cascade? 
It is an Object Detection Algorithm used to identify faces in an image or a real time video. 
The algorithm uses edge or line detection features proposed by Viola and Jones in their 
research paper “Rapid Object Detection using a Boosted Cascade of Simple Features” published in 2001.


The features in Haar Cascade is stored in XML files. I have used "haarcascade_fullbody.xml"
for detecting the face and "haarcascade_eye.xml" for detecting the eyes. I have downloaded these files
from Haar Cascade GitHub repository [[link](https://github.com/opencv/opencv/tree/master/data/haarcascades)].
Then, I created a body classifier, initiated video capture for video file, looped once video is successfully loaded, read first frame,changed the color scale to gray for speeding up the task,  passed frame to the body classifier and extracted bounding boxes for any body identified.


### Demo:
![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/75041273/136671446-c381bcac-5640-4898-a05e-b52a40f9e5c4.gif)

### Installation:
The Code is written in Python 3.7.3 If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:

##### 1. First create a virtual environment by using this command:
```bash
conda create -n myenv python=3.7
```
##### 2. Activate the environment using the below command:
```bash
conda activate myenv
```
##### 3. Then install all the packages by using the following command
```bash
pip install -r requirements.txt
```
##### 4. Open the .ipynb file inside Jupyter Notebook and run the cells.

##### Make sure to change the directory to the root folder. The folder structure should be same as of this repository otherwise it will throw error. 

