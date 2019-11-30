# Image Classification and retrieval using Deep learning

This project uses the popular benchmark dataset in computer vision called CIFAR-10. I have reduced the data to just 4 categories = {'cat','bird','automobile','dog'}.

## Image Classification

  1. Firstly a logistic classifier is trained on raw pixels of images.
  2. A prediction is made with this simple model on images.
  3. Deep features are used to train another logistic classifier model.
  4. The deep feature model is then used to make prediction and its evaluated for its accuracy.
Its found that the deep feature model performs better than the simple model.

## Image Retrieval

A nearest neighbour model is built using deep features for image retrieval.