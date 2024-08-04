# Image_Encryption

This notebook shows the working of Haar wavelet model in image encryption and decryption by using a medical Scan of brain as an input image , sample image size as text representing patient data and random numbers to form an image representing hospital logo

The aim of the project is to embed patient information and hospital logo in an single image to optimise the communication cost for machine learning/AI model to study/learn or analyse the medical aspects

# Haar Wavelet

Lossless encryption methods are more applicable than lossy encryption methods when marginal distortion is not tolerable. Haar wavelet is one of the best mathematical tools in image cryptography and analysis.

In this project the image is transformed into the frequency domain using the Haar wavelet transform, then the image is 
sub-divided into Region of interest and Region of Non interest for secure encrypted of patient data and hostpital logo in a such way that guarantees a secure, reliable, and an unbreakable form.

Later both the sub-divided images are recompiled to form the origianl image and for testing Gausian Noise function is used to determine the scattering of image that can be caused by noide or unwanted data in real life environment
