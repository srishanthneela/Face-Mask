# Face-Mask
Image and Real time webcam face detection, protect yourself from COVID19 with a virtual face mask.

Utilize tensorflowjs facemesh model.

## Live Demo
**[https://bensonruan.com/mask-for-trump-with-tensorflowjs-facemesh-model](https://bensonruan.com/mask-for-trump-with-tensorflowjs-facemesh-model)**

![mask-for-Trump](https://bensonruan.com/wp-content/uploads/2020/05/Mask_for_Trump.gif)


## Installing
Clone this repository to your local computer
``` bash
git https://github.com/bensonruan/Face-Mask.git
```
Point your localhost to the cloned root directory

Browse to http://localhost/index.html 

## Face Keypoints 
The facemesh detected keypoints that used for overlay the mask:
* Forehead : 10
* Left Cheek : 234
* Chin : 152
* Right Cheek : 454


## Put Mask On
* Click on 'Put Mask On' button to detect face on image and cover by mask
* Turn on the Webcam switch and allowing the browser to access your webcam 
* Wait for a few seconds to Load Model for hand tracking
* Choose the face mask you lik to try on, watch yourself cover up 

![facemesh-mask-demo](https://bensonruan.com/wp-content/uploads/2020/05/facemesh_mask_webcam_demo_short.gif)

## Notes
Please note that on iOS Safari, cameras can only be accessed via the https protocol 

## Library
* [jquery](https://code.jquery.com/jquery-3.3.1.min.js) - JQuery
* [webcam-easy.js](https://github.com/bensonruan/webcam-easy) - javascript library for accessing webcam stream and taking photos
* [facemesh](https://github.com/tensorflow/tfjs-models/tree/master/facemesh) - MediaPipe Facemesh is a lightweight machine learning pipeline predicting 486 3D facial landmarks to infer the approximate surface geometry of a human face 
