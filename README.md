# Automatic-Curation-of-Images-using-Caffe-and-YOLO

Ever since a deep convolutional neural network with an error rate of less than 16% was used to win
2012’s ImageNet Large Scale Visual Recognition Challenge, deep learning has become immensely
popular for image recognition tasks. While our first brush with neural networks was with Bishop’s
Neural Networks for Pattern Recognition, it is its reincarnation as the powerful deep learning that
has galvanized our interest. Our study on limiting the ability of face recognition algorithms using
Eigenfaces and K-same approach got us asking the following questions:
What makes a face a face and how the image of a face could be different from images of
other objects? Could the system actually detect if the image being recognized was that of a human
face? As we dug deeper, we became interested in the automatic curation of images primarily in
order validate the contents of images against their respective descriptions. we intend to identify the
images that conform to a certain scene’s verbal definition. It means that upon being given a verbal
description, relevant images can be returned barring images that do not match the description. Here,
we will be using two frameworks namely Caffe and YOLO.

We intend to train the scene classification model using the Caffe and use YOLO as a final step of
verification in determining the object to scene relevance. Upon training more and more images with
both these models and by storing the predictions obtained by running images on both Caffe and
YOLO, the number of search labels can be significantly increased for an image thereby making
image curation more accurate. We value this project as an independent exercise in learning various
practical aspects of programming machine learning algorithms.

The application of such a method could change how images appear in any website. Search
can be made possible based not on the image file’s name but rather using the image’s contents and
therefore, image curation could enable a user to view content based on his/her past history of
preferences thereby enabling the user to find exactly what he/she is looking for with an interface
that changes as per his/her preferences and needs. The user may also be recommended similar
images based on what he/she is already viewing. Image validations based on content of the image
and its related description is one more application.
