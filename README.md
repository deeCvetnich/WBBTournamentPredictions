# Predicting Game Winners in the Women's March Madness Tournament

## Goal
  The goal of this project is to create a machine learning model to predict winners in the women's March Madness tournament. 
 
## How?
  This project will be completed by webscraping women's NCAA tournament game data from https://www.sports-reference.com/cbb/seasons/ and pages able to be reached from this page. This data will then be cleaned in preparation for input into the machine learning algorithms. Several algorithms will be tested in order to determine which gives the best results. Four seasons of data (2022, 2021, 2019, 2016) will be set aside for testing and validation purposes. 
  
###### Software, Languages Used
All code for this project is written entirely in Python, with the use of Jupyter Notebook. HTML and CSS are used in the visualization of the predicted brackets.

## Results
  - 61% Accuracy
  - 2022 Tournament
    - Able to predict national champion
    - Predicted bracket scored 1190 / 1920 points (according to ESPN Tournament Challenge Rules)
    - Predicted bracket correctly predicted 39/63 (62%) of game winners in tournament

## Future Direction
This project can be continued by adding more seasons of data to the training if or when they come available. It would be ideal to essentially rotate out the oldest of the testing set and place it into the training set as newer seasons can be added to the testing data. More advanced statistics could also be added to possibly increase the accuracy of the model. Implementation of the model and bracket producer would be of more use within a webpage or phone application, so another future step could be implementing this.

## Scope
  This project is being completed in order to fufill the CPSC-470: Senior Project credit at Roanoke College, located in Salem, VA. 
