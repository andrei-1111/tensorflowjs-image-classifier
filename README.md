# tensorflowjs-image-classifier

You will first load and run a popular pre-trained model called MobileNet for
image classification in the browser. You will then use a technique called
"transfer learning", which bootstraps our training with the pre-trained
MobileNet model and customizes it to train for your application.

`mobilenet_inference.html` -
Allows to make predictions on images that come through the webcam in real-time.

`custom_classifier.html` -
Allows to capture images for each of the three classes.  Each time you click one
of the "Add" buttons, one image is added to that class as a training example.
While you do this, the model continues to make predictions on webcam images
coming in and shows the results in real-time.

Sources:

- [Google TensorFlow.js Transfer Learning Image Classifier](https://codelabs.developers.google.com/codelabs/tensorflowjs-teachablemachine-codelab/index.html)
- [TensorFlow JS](https://www.tensorflow.org/js/tutorials)
- [MobileNet](https://github.com/tensorflow/models/blob/master/research/slim/nets/mobilenet_v1.md)
