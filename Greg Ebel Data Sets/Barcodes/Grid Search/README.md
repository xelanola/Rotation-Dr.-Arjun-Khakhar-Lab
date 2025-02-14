1. Grid_Search_1.0.ipynb

This code allows you to grid search either individual are coupled hyperparameters for Optimus 5 Prime.

The code will run the parameters in triplicate and print out the r squared value generated for each option of the parameter.
It also produces a dataframe either with the individual results or grouped results that show mean r squared values.
It also produces graphs to visually represent the grid search.

Lastly, if you run multiple hyperparameters on the grid search, it will produce a dataframe with all the results of the grid search.
^This cannot be graphed.

2. Grid_Search_1.0_Refined.ipynb

This is identical to the previous file but was used for narrowing down the grid search once individual hyperparameter values were identified.
This was made so that the code in the original grid search does not have to be modified.

3. Grid Search 02-28-23.csv

This is the dataframe output Grid Search completed for Optimus 5 Prime in the context of the data  

Barcodes/Alligned Barcodes-50bp flanks/Barcode_mg_133bp_Alligned.pkl

The columns represent all the hyperparameters tested with each row showing a different combination of the values tested.
The R squared value for each combination is provided in the "R Squared" column.