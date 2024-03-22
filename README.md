# HUMAN-EMOTION-ANALYSIS-USING-MACHINE-LEARNING



## Title of the Project
Face detection has been around for ages. Taking a step forward, human emotion displayed by face and felt by brain, captured in either video, electric signal (EEG) or image form can be approximated. Human emotion detection is the need of the hour so that modern artificial intelligent systems can emulate and gauge reactions from face. This can be helpful to make informed decisions be it regarding identification of intent, promotion of offers or security related threats. Recognizing emotions from images or video is a trivial task for human eye, but proves to be very challenging for machines and requires many image processing techniques for feature extraction.

## About
<!--Detailed Description about the project-->
Human emotion detection is implemented in many areas requiring additional security or information about the person. It can be seen as a second step to face detection where we may be required to set up a second layer of security, where along with the face, the emotion is also detected. This can be useful to verify that the person standing in front of the camera is not just a 2-dimensional representation.Another important domain where we see the importance of emotion detection is for business promotions. Most of the businesses thrive on customer responses to all their products and offers. If an artificial intelligent system can capture and identify real time emotions based on user image or video, they can make a decision on whether the customer liked or disliked the product or offer.

## Features
<!--List the features of the project as shown below-->
- Facial Landmarks: Detecting key points on the face such as eyes, nose, mouth, and eyebrows. These landmarks provide spatial information about facial expressions.
- Data Collection: Gathering a diverse dataset of facial images or videos annotated with corresponding emotions. These emotions may include happiness, sadness, anger, surprise, fear, disgust, and possibly others.
- Preprocessing: Cleaning and preprocessing the collected data to ensure uniformity and consistency across images or videos. This may involve normalization, resizing, and standardization of images, as well as filtering out irrelevant information.
- Feature Extraction: Identifying relevant facial features or landmarks that convey emotional cues. Common features include eyebrow position, eye openness, mouth shape, and overall facial expressions.



## Requirements
<!--List the requirements of the project as shown below-->
* Operating System: Requires a 64-bit OS (Windows 10 or Ubuntu) for compatibility with machine learning frameworks.
* Development Environment: Python 3.6 or later is necessary for coding the sign language detection system.
* machine Learning Frameworks: TensorFlow for model training, MediaPipe for hand gesture recognition.
* Image Processing Libraries: OpenCV is essential for efficient image processing and real-time hand gesture recognition.
* Additional Dependencies: Includes scikit-learn, TensorFlow (versions 2.4.1), TensorFlow GPU, OpenCV.

## System Architecture
<!--Embed the system architecture diagram as shown below-->


![architecture](https://github.com/K1540438/HUMAN-EMOTION-ANALYSIS-USING-MACHINE-LEARNING/assets/84171243/6966ad32-67fd-4bb0-8c5c-cd80f5333024)

## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Name of the output

![output1](https://github.com/K1540438/HUMAN-EMOTION-ANALYSIS-USING-MACHINE-LEARNING/assets/84171243/e7a9e838-ad1e-4f17-9d27-529044e7f8d6)


#### Output2 - Name of the output
![output2](https://github.com/K1540438/HUMAN-EMOTION-ANALYSIS-USING-MACHINE-LEARNING/assets/84171243/0abe819a-7dcc-4573-add7-bc5474e6d118)


Detection Accuracy: 89.1%
Note: These metrics can be customized based on your actual performance evaluations.


## Results and Impact
<!--Give the results and impact as shown below-->
For testing out the model, we trained using the dataset and test using some images. The logistic regression model was able to identify the basic happy and surprise emotions. Although, with fearful, contemptuous, sad and disgust the algorithm predicted wrong classes as all the test subjects were not giving same expressions for each of the mentioned emotion. We used only 68 point facial landmarks for this experiment as features. As there was no neutral expression in training dataset, it was not identified from the test set. Happy and Surprise were detected the most and most of the other emotions were misclassified as Happy and Disgust.

## Articles published / References
1. H. Ebine, Y. Shiga, M. Ikeda and O. Nakamura, "The recognition of facial expressions with automatic detection of the reference face," 2000 Canadian Conference on Electrical and Computer Engineering. Conference Proceedings. Navigating to a New Era (Cat. No.00TH8492), Halifax, NS, 2000, pp. 1091-1099 vol.2.
2. M. Dahmane and J. Meunier, "Emotion recognition using dynamic grid-based HoG features," Face and Gesture 2011, Santa Barbara, CA, 2019.
