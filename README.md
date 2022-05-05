# Neural_Network_Charity_Analysis

## Overview
* The purpose of this analysis was to use machine learning to create a neural network that would be able to predict whether applicants would be successful if funded by Alphabet Soup. 
## Results
### Data Preprocessing
* **The main variable that was targeted for this model:** 
    * "IS_SUCCESSFUL" — which determined if money was used effectively
* **The other variables that were features in the model:**
    * "APPLICATION_TYPE" — Alphabet Soup application type
    * "AFFILIATION" — Affiliated sector of industry
    * "CLASSIFICATION" — Government organization classification
    * "USE_CASE" — Use case for funding
    * "ORGANIZATIO"N — Organization type
    * "STATUS" — Active status
    * "INCOME_AMT" — Income classification
    * "SPECIAL_CONSIDERATIONS" — Special consideration for application
    * "ASK_AMT" — Funding amount requested
 * **Variables that were removed from the Model:**
     *  "EIN" and "NAME" — Identification columns
### Compiling, Training, and Evaluating the Model
* **Neural Network Overview**
    * Two layers were implemented with 80 and 30 neurons and both layers were activated with ReLu.
        * This was chosen for the starting point and then was to be adjusted afterwards to achieve optimal accuracy.


![goals](https://github.com/Leehudson514/Neural_Network_Charity_Analysis/blob/main/layers.png)

    * **Accuracy Target was 75%** 
        * Accuracy level achieved was 73% 
        * The target was not achieved after multiple attempts at adding layers, changing the number of neurons and attempting different activations.  
## Summary
* Overall the model did not achieve the desire results of 75% even after multiple attempts of adjustments. 
* Going forward I would recommend the client to test with the random forest classifier because of its capabilities with larger data sets it is less influenced by outliers and it is better with binary data which should result in higher accuracy with regards to this data set.
