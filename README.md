# Face-Detection-on-Android
&#160; &#160; &#160; &#160;This is an example of face detection based on dlib, tested on Android.

&#160; &#160; &#160; &#160;Dlib is a well-known library with interfaces for C++ and Python. Using dlib can greatly simplify development, such as face recognition, feature point detection, can be easily achieved.

&#160; &#160; &#160; &#160;In this demo, we used the 68 keypoint detection model in the dlib library,model file at *Face-Detection-on-Android/dlib-android-app/app/src/main/res/raw/shape_predictor_68_face_landmarks.dat*.

&#160; &#160; &#160; &#160;You can also download other model tests, link here：http://dlib.net/files/, just need modify the code for the face detection part.

&#160; &#160; &#160; &#160;The code refers to https://github.com/tzutalin/dlib-android-app, the code has made some modifications,mainly to change the rear camera to the front camera, which is convenient for us to test. Currently, only the front camera is supported for the key point detection of the face, and the mobile phone flip is not supported.

&#160; &#160; &#160; &#160;Environmental requirements:

&#160; &#160; &#160; &#160; **·** Android Studio

&#160; &#160; &#160; &#160; **·** Android SDK

&#160; &#160; &#160; &#160; **·** Java

&#160; &#160; &#160; &#160;The mobile phone is Huawei Mate8, the actual test is as follows:

&#160; &#160; &#160; &#160;![image](https://github.com/HuiZhou-xmu/Face-Detection-on-Android/raw/master/gif/face_detection.gif)

&#160; &#160; &#160; &#160;The effect of the detection is real-time, and it can be basically detected when the side/down/up face is not large. If we are far away from the camera, the effect of detecting tiny faces will be poor.
