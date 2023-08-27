## Setting the directory in Google Drive

###  Create a folder DL with the following sub-folders

   
![folderstructure](https://github.com/comeall11/AOHRSI_KamalAndSerge/assets/6022346/8b1078d7-0ae1-4ad8-bbec-ac35d56de64b)


###  Descriptions of folders:
   
 #### - Data: To store the input data for training, validation, testing and inference
 - Arrays: stores the training and validation data (image and landslide footprints)
 - Inference: stores the satellite imagery of the area of interest to map the landslide
 
 #### - Results: To store the processing results and outputs
 - csv: Tabular file storing the accuracy parameters values for each type of model with different hyperparameters
 - plots: Graphical representations of the various models tested using the different hyperparameters in DL model
 - weights: weight file for each model run with different hyperparameters
 - Predictions: Raster and vector file of the predicted/detected landslide using the best model and satellite imagery.
     
### Run the "Automated_landslide_mapping.ipynb" using the suitable hyperparameters in Google Collaboratory
