# Human Posture Recognition System

* The objectives of the project are to -
  * Make a dataset for posture recognition.
  * Use the dataset to create a CNN classifier.
* The following postures have been considered -
  * Bending
  * Lying
  * Sitting
  * Standing
* The programs have been written using Python3 in Google Colab.

## Dataset

* The dataset is available as downloadable zip file under *Dataset* folder.
* The size of images available are 256 x 256 and 512 x 512.
* Each of the zip file follow the following directory structure -

  ```[markdown]
  .
  |--Training
  |  |--Bending
  |  |--Sitting
  |  |--Lying
  |  |--Standing
  |
  |--Validation
  |  |--Bending
  |  |--Sitting
  |  |--Lying
  |  |--Standing
  ```

## Structure Description

* *Dataset* - Contains the dataset.
* *ScratchModel* - Contains the program used for training the classifier from scratch. It also contains a script to make prediction using the saved model.
* *TransferLearning* - Contains the pre trained weight files and the programs for performing transfer learning.
* The pre trained model can be downloaded from *./ScratchModel/model/* and executed using *./ScratchModel/model/predict.ipynb*
