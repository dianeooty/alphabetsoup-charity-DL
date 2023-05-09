# deep-learning-challenge
Our business team for Alphabet Soup, a nonprofit foundation, was tasked with building a learning model to help predict the applicants that has the best chance of success for their business ventures.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Screenshots](#screenshots)
* [Setup](#setup)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)


## General Information
Using the charity_data.csv at https://static.bc-edx.com/data/dl-1-2/m21/lms/starter/charity_data.csv, I created a training model for the predictions.  The data was read into a pandas dataframe and then preprocessed before training.  For the preprocess, irrelevant columns such as EIN and NAME were removed.  Then each column was reviewed to determine if binning the rare values would be a good approach to maximixe accuracy.  Then the target variables and categorical values were determined and assigned as 'X' and 'y'.  I used get_dummies() to encode the 'X' values before passing it to the train_test_split function to get the training and testing datasets.  The training dataset was then scaled using StandardScaler() and fitted with the transform function.

With the preprocessing complete, I created a model using TensorFlow and Keras where I determined the activation types, hidden layers, input dimensions and number of neurons.  After training the model, I then evaluated the loss and accuracy.  The results for this model showed a loss of 0.5541 and accuracy of 0.7304.

In order to improve the accuracy, I optimized the model by making adjustments to the model structure and preprocessed data.  A total of three optimizations were completed and the highest accuracy was 0.7341.  This was not a significant difference as the goal was to achieve an accuracy higher than 75%.  Further model testing and optimization is still needed.  


## Technologies Used
- Google Colab
- Jupyter Notebook
- Pandas
- TensorFlow and Keras
- Sklearn


## Screenshots
![1](https://github.com/dianeooty/deep-learning-challenge/assets/117790100/9ea25433-747b-4e7d-800f-e42c521b7aa5)
![2](https://github.com/dianeooty/deep-learning-challenge/assets/117790100/6386f585-bbf8-425a-8a4c-935f25eeca2a)
![3](https://github.com/dianeooty/deep-learning-challenge/assets/117790100/9f0b16bb-d584-4192-9eb2-c16b429b353c)
![5](https://github.com/dianeooty/deep-learning-challenge/assets/117790100/f86b6449-d7d2-4ae1-934e-4165736b8c8e)
![4](https://github.com/dianeooty/deep-learning-challenge/assets/117790100/b40ced95-0ef4-4b9a-b800-c789cd0b97ac)
![6](https://github.com/dianeooty/deep-learning-challenge/assets/117790100/fa2c9862-1d11-4cdf-8610-07734581a9d1)
![7](https://github.com/dianeooty/deep-learning-challenge/assets/117790100/2d365e4e-b1b9-43fd-b97c-c33c71e11812)
![8](https://github.com/dianeooty/deep-learning-challenge/assets/117790100/7fa46b88-1f1b-4a6b-a365-d7c635d66192)
![9](https://github.com/dianeooty/deep-learning-challenge/assets/117790100/e3fceaa2-f1f8-43d2-b112-7946d5f0d093)
![10](https://github.com/dianeooty/deep-learning-challenge/assets/117790100/ce7b8355-d836-42bc-a4d9-d6c7bab36ebc)


## Setup
You can access the models by loading the files to Google Colab or Jupyter Notebook and running the codes.


## Project Status
Project is complete and currently not being worked on.


## Room for Improvement
Further model testing is needed to obtain an accuracy of higher than 75%. 


## Acknowledgements
Many thanks to the instructional team and David Chao.


## Contact
Created by Diane Guzman

