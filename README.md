# IE4483_Project

AI and Data mining project

Objective of Project:
We were tasked to write an algorithm to classify whether an image contains either a dog or a cat. Which is easy for the humans, but computers will find it difficult to differentiate them.

The process is broken down into 5 steps.

1. Loading and preparing the data
   • Datasets are broken down into 3 files, Train, Val and Test.
2. Data processing
   • Pre-process our input images to improve classification performance.
3. Model selection
   • Design and develop a classification model that can classify dog and cat images.
4. Model Training
   • Test with different model parameters to get better classification results.
5. Prediction.
   • Trained model can be used to correctly classify the dog and cat images in the test set.

We were given some guiding questions for the report.
a. State the amount image data that you used to form your training set and testing set. Describe the data pre-processing procedures and image augmentations (if any). (10% marks)
b. Select or build at least one machine learning model (e.g., CNN + linear layer, etc.) to construct your classifier. Clearly describe the model you use, including a figure of model architecture, the input and output dimensions, structure of the model, loss function(s), training strategy, etc. Include your code and instructions on how to run the code. If non-deterministic method is used, ensure reproducibility of your results by averaging the results over multiple runs, cross-validation, fixing random seed, etc. (20% marks)
c. Discuss how you consider and determine the parameters (e.g., learning rate, etc.) / settings of your model as well as your reasons of doing so. (5% marks)
d. Report the classification accuracy on validation set. Apply the classifier(s) built to the test set. Submit the “submission.csv” with the results you obtained. (20% marks)
e. Analyse some correctly and incorrectly classified (if any) samples in the test set. Select 1-2 cases to discuss the strength and weakness of the model. (10% marks)
f. Discuss how different choice of models and data processing may affect the project in terms of accuracy on validation set. (10% marks)
g. Apply and improve your classification algorithm to a multi-category image classification problem for Cifar-10 dataset (https://www.cs.toronto.edu/~kriz/cifar.html). Describe details about the dataset and classification problem that you are solving. Explain how your algorithm can tackle this problem, and what changes you make comparing to solving Dogs vs. Cats problem. Report your results for the testing set of Cifar-10. (15% marks)
h. Train the classifier for (g), while some of the classes in Cifar-10 training dataset contains much fewer labelled data. How can you improve your algorithm to tackle the data unbalancing issue? Describe and justify at least 2 approaches you use. (10% marks)
