# EMNIST Classifier with CNNs

Final project for the Building AI course

## Summary

This project involves building a Convolutional Neural Network (CNN) to classify images from the EMNIST dataset. The goal is to achieve accurate character recognition, which can then serve as a foundation for more complex AI-driven applications. All details and explanation of the implementation are contained in the attaches `.ipynb` file in the main branch of this repository. **Please consult `Juan_Trobajo_Flecha_Classification_CNN_EMNIST.ipynb` for further technical information on the project.**

## Background

Character recognition is a crucial component in various applications such as automated data entry, license plate recognition, and postal mail sorting. The ability to accurately classify characters can significantly streamline these processes. My personal motivation for this project is to deepen my understanding of CNNs and their applications in image processing, which I find both challenging and intriguing.

This project addresses several problems:

* Automating the reading of handwritten characters.
* Enhancing accuracy in character recognition tasks.
* Providing a basis for more complex AI applications in the future.

## How is it used?

The CNN model is used to classify images from the EMNIST dataset. The process involves the following steps:

1. Preprocessing the EMNIST dataset.
2. Training the CNN model on the training set.
3. Evaluating the model's performance on the test set.
4. Using the trained model to predict characters from new images.

This solution is essential in environments where quick and accurate character recognition is needed, such as postal services, banks, and data entry jobs. The primary users are developers and researchers working on optical character recognition (OCR) systems.

## Data sources and AI methods

The data for this project comes from the EMNIST dataset, which is an extension of the MNIST dataset and includes more characters. The dataset is publicly available and widely used in the field of image processing and machine learning.

The primary AI technique used in this project is Convolutional Neural Networks (CNNs), which are particularly effective for image classification tasks. The model is implemented using Python and popular machine learning libraries such as TensorFlow and Keras.

[EMNIST Dataset](https://www.nist.gov/itl/products-and-services/emnist-dataset)

## Challenges

This project does not solve all problems related to character recognition. Some limitations and ethical considerations include:

* Handling poor-quality or corrupted images.
* Bias in the dataset that might affect the model's accuracy.
* Ensuring the privacy of any data used for training the model.

## What next?

To enhance this project further, the following steps could be taken:

* Expanding the model to handle more complex datasets.
* Improving the preprocessing steps to handle a wider variety of image conditions.
* Integrating the model into a full OCR pipeline for real-world applications.

To achieve these goals, additional skills in advanced image processing, model optimization, and software integration would be beneficial.

## Acknowledgments

* The EMNIST dataset creators.
* Any other sources of inspiration and assistance mentioned in the notebook itself.
