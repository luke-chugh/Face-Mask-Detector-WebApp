# Face Mask Detector WebApp: [[WebApp link]](https://share.streamlit.io/luke-chugh/face-mask-detector-webapp/main/app.py)

 **MobileNet-V2** was implemented to classify images as belonging to **Mask** or **WithoutMask** categories which resulted in 99.2% accuracy. Then **Caffe Model** was implemented to make frames on faces and finally **CV2** library was used to label each of these frames with class labels + confidence/probability. The dataset can be found [here](https://www.kaggle.com/datasets/ashishjangra27/face-mask-12k-images-dataset). 

# Below is the screenshot of my web app:

![Capture](https://github.com/luke-chugh/Face-Mask-Detector-WebApp/blob/main/screenshots/2.png)

# Installation
To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```
To run this app in your local machine open a command prompt or terminal in the cloned directory and run:
```bash
streamlit run app.py
```
# Author
[Luke Chugh](https://www.linkedin.com/in/luke-chugh-2b2043181/)

