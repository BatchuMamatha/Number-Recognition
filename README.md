Number Recognition with Machine Learning - Data Science Internship Project

This repository contains the implementation of a Number Recognition system, a project developed during my Data Science Internship at Bharat Intern. The goal of this project was to build a machine learning model that can accurately identify handwritten digits from images.

Dataset:
The model was trained on the popular MNIST dataset, which consists of 28x28 grayscale images of handwritten digits from 0 to 9. The dataset contains 60,000 training images and 10,000 test images, making it a suitable choice for training a number recognition model.

Methodology:

    Data Preprocessing: The images were preprocessed to normalize pixel values and enhance the quality of the dataset.

    Feature Extraction: The images were flattened into a one-dimensional array, and feature scaling was performed to ensure consistent training across all samples.

    Model Selection: Different machine learning algorithms were explored, including Support Vector Machines (SVM), Random Forest, and Convolutional Neural Networks (CNN).

    Model Training: The selected model was trained on the training dataset and tuned using cross-validation techniques to achieve the best performance.

Dependencies:

The following Python libraries were used in this project:

    numpy
    pandas
    matplotlib
    scikit-learn
    tensorflow (for CNN implementation)

Open the Jupyter notebooks in the notebooks folder to view the step-by-step implementation.

To use the pre-trained model for number recognition, refer to the example code in the notebooks or the model folder.

Results:

The final model achieved an accuracy of over 95% on the test dataset, demonstrating its effectiveness in accurately recognizing handwritten digits.

Feel free to explore the project and use the code for your own number recognition tasks. If you have any questions or feedback, please don't hesitate to reach out. Happy coding! 🚀
