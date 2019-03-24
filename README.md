# denagari-recognition
Devanagari handwriting recognition
DATA 
This is a dataset of Devanagari Script Characters. It comprises of 92000 images [32x32 px]. There are 1024 input features of pixel values in grayscale (0 to 255). The column "character" represents the Devanagari Character Name corresponding to each image.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
DEPENDDENCIES:
Numpy
Pandas
Matplotlib
Seaborn
Sckit-Learn
Keras (Tensorflow Backend)
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
IMPLEMENTATION:
Creating .h5 model first using keras and devnagari dataset available and then training with accuracy 95.9%
and then using taht model to predict and process image using cv2 and keras test accuracy 94.33%
