
1. Initial Barcodes From Greg
This folder contains all the data sets given by Dr. Greg Ebel as well as all of their manipulations.

2. More Barcodes From Fitz
This folder has all the items given to be my Emily Fitzmeyer from Dr. Greg Ebel's lab on 03-03-23.

This has all input files and all midgut files.



3. training_MRL_CNN_Barcode.ipynb and training_MRL_CNN_test.hdf5

This is the Optimus 5 Prime model but the columns have been modified to make it accept the Barcode Data instead.



4. Compiling Barcode Data Sets.ipynb

This is a piece of code that takes all the data files, converts them into csv files and then concatenates them into one csv file.

However, since there are multiple sequenced regions, this should not be done. The code remains useful for future projects.


5. Barcodes Change in Count.ipynb

This code takes the CSV files and generates Barcode_Input_vs_mg.csv and .pkl
Ultimately this code can be used to get the frequency of sequence counts from any data set.



6. Barcodes Allignment.ipynb

This code takes the barcode sequences in Alligned Barcode or CSV Data and adds the 50bp upstream and downstream of the barcode from the WNV sequence.


7. Grid Search

This contains all the code and data generated to perform a grid search of training_MRL_CNN_Barcodes.ipynb

