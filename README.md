# Pipeline
<img width="1533" height="792" alt="pipeline" src="https://github.com/user-attachments/assets/88516837-83fd-4c70-8675-a7516179f52c" />
This paper proposes a novel talking head generation method that combines layered viewpoint simulation (LVS) and continuous lighting simulation (CLS). LVS simulates multiple viewpoints through the multi-scale features of the video frame to construct the global depth representation, which can improve the accuracy of volume density estimation and enhance detail description. CLS simulates multiple lighting through brightness changes of continuous video frames to construct the global brightness representation, thereby alleviating color accumulation errors and eliminating blur. Extensive experiments demonstrate that our method significantly improves the detail quality compared to the state-of-the-art methods.

## **Demo**
https://github.com/user-attachments/assets/de8670aa-ce1f-45f4-abf7-33d85685f6e9


## **Dataset**
Our datasets come from public interviews or TV shows.

## **Highlights**
-  We introduce layered viewpoint simulation (LVS) to construct the global depth representation, which enhances the detail expression.
-  We propose continuous lighting simulation (CLS) to construct the global brightness representation, which eliminates blurring artifacts.

## **Installation**
-  We train and test based on Python 3.8
-  ffmpeg: ```sudo apt-get install ffmpeg```
-  To install the dependencies run: ```pip install -r TalkingHead-Simulation.txt```

## **Citation**
Consider citing as below if you find this repository helpful to your project:



## **Contact**
Our code is for research purposes only. More details will be released shortly. If you have any questions, please contact us: dongbiao@bit.edu.cn
