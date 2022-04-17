# Digit Recognizer

This repository contains models for easily classifying digits using binary images. The models don't require special hardware and can be quickly run on an everyday laptop.

Only the digits 1-9 are covered.

The training data consists of 384x384 binary images extracted from sudokus.

## How to use

See the [src/examples.ipynb](https://github.com/andrinmeier/digit-recognizer/blob/main/src/examples.ipynb) file for an example on how to use the pretrained SVM classifier.
Please note that the model was trained on images that were resized to 64x64.
The features of an image are encoded using histogram of oriented gradients (HOG).
