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
![Example screenshot](./img/screenshot.png)
<!-- If you have screenshots you'd like to share, include them here. -->


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

