<<<<<<< HEAD

# FaceMusic
This app detects your emotions based on your picture and creates playlists according to your mood.  

## The classification
To detect faces on an image the application uses [ML Kit](https://developers.google.com/ml-kit).
After detection complete the face image area converted into greyscale 48*48 pixel format, each pixel represents as [0, 1] float number.
Finally, converted area fed to the [TensorFlow Light](https://www.tensorflow.org/lite/guide) convolutional neural network model (simple_classifier.tflite).
The model provide output that consist of probabilities for each class: angry, disgust, fear, happy, neutral, sad, surprise.  
<img src="/images/example.png" width="288" height="512">

=======
# FaceMusic
>>>>>>> parent of b1f328a (add face rec code and start ditection btn)
