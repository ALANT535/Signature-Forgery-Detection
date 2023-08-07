
WHY IS SIGNATURE FORGERY DETECTION SO IMPORTANT?

Signature forgery detection is crucial for preserving the integrity of legal, financial, and personal documents. It safeguards against fraudulent activities, identity theft, and unauthorized transactions. Reliable detection mechanisms, such as handwriting analysis and advanced technology, help maintain trust in signatures as a secure form of verification, ensuring the authenticity of important interactions and preventing potential losses and legal disputes. Detecting signature forgery prevents fraud, identity theft, and legal disputes, preserving the reliability of signatures as trustworthy verification tools.


PROJECT DETAILS

This project uses the libraries of Tensorflow and Keras to implement a Convolutional Neural Network; used to predict whether an input image was a forgery or not. To process the image, the library of OpenCV was used. The standard machine learning libraries of pandas and numpy were also used to manipulate and use the numerical arrays formed from converting the images. While processing the image, it was also chosen to use a single color gray-channel; instead of the three color RGB color channel, so as to reduce computation time, considering that the color of the signature did not add a lot of value to the prediction.

The dataset used for thhe project consisted of 48 images of a person, of which 24 were real and 24 fake. Due to the dataset being so small and the unavailability of larger datasets sutitable to train the model, the results may not be representative of taking a much larger dataset to train and test the model. However, that will be tried out either by creating our own dataset or by finding a bigger,better dataset. As per metric values, an accuracy of 95-100% accuracy was measured; which could give the impression of a little bit of overtraining; but the dataset is really too small to remark on that aspect of the model.

In the future, an advanced signature forgery detection system could incorporate AI and machine learning, achieving higher accuracy and efficiency. It might offer real-time analysis, integration with digital platforms, and secure authentication methods, bolstering document security, reducing fraud, and enhancing trust in online transactions and legal processes.


<!---
ALANT535/ALANT535 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
