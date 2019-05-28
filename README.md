# OutcomePrediction
Jupyter Notebook to predict whether or not students successfully complete training courses. Code should serve as a relatively general base for binary or multi-class predictions.

Originally produced over 2 working days for a Hackathon.

## The Algorithms
The notebook utilises 5 different approaches to ML implemented in sklearn and TensorFlow.
1. Naive Bayes
2. Linear Regression
3. Support Vector Machine
4. Random Forest
5. Multi-Layer Perceptron (Neural Network)

All code is inline to improve portability and for hackathon submission.

## The Data
The data is from Primary Education and provides information on ~12,000 students. This includes demographic, geographical region, essay scores, module completion etc.

Un-obscured data source is unfortunately not available to be posted publicly. Picked data files provide usable dataframes for running the notebooks.

## The Aim
Predict whether or not a given student will finish a training course (0 = Not Complete, 1 = Complete)

## How can I run this myself?
Upload the data_process notebook to Google Collaboratory and upload the pickle files to the root directory.
