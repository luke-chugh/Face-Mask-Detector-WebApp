# Face Mask Detector WebApp: 

![](https://img.shields.io/badge/python-3.7-blueviolet)
![](https://img.shields.io/badge/tensorflow-2.9.0-fuchsia)
![](https://img.shields.io/badge/OpenCV-4.5.5-gold)
![](https://img.shields.io/badge/streamlit-1.9.1-brightgreen)

 **MobileNet-V2** was implemented to classify images as belonging to **Mask** or **WithoutMask** categories which resulted in 99.2% accuracy. Then **Caffe Model** was implemented to detect all the faces with frames in each image and finally **CV2** library was used to label each of these frames with their respective class labels + confidence/probability. The dataset which was used to train  **MobileNet-V2** can be found [here](https://www.kaggle.com/datasets/ashishjangra27/face-mask-12k-images-dataset). 
 
This WebApp also has a **slider** which one can control to see only those detections which have greater probability of belonging to both the classes than the confidence set by the slider

# Below is the screenshot of this WebApp:

![Capture](https://github.com/luke-chugh/Face-Mask-Detector-WebApp/blob/main/screenshots/2.png)

# Installation:
To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```
To run this app in your local machine open a command prompt or terminal in the cloned directory and run:
```bash
streamlit run app.py
```
# Author:
[Luke Chugh](https://www.linkedin.com/in/luke-chugh-2b2043181/)

