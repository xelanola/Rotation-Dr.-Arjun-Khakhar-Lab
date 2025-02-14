1. egfp_unmod_1.csv and egfp_unmod_1.pkl

^the pickle file is the one that was originally used in the paper that used the Optimus 5 Prime model.
The csv file is the same exact data but in csv format for seeing the data.

2. Optimus 5 Prime (My Mod)

This is the Optimus 5 Prime model. In the github repository it is known as training_MRL_CNN.ipynb.
This is the ML model that takes sequence data and predicts mean ribosomal load as the output.
It has some changes from the original code that make it work.

*model works specifically in the environment labwork*


3. Random Sequence Generator.ipynb

This is code that makes a dataframe similar in shape to the egfp_unmod_1 data set.
The code generates random sequences and can generate polyAs at random locations in the sequence.
The code has rl values normalized. 
This code does not work on the Optimus 5 Prime model because there is too much noise because the sequence is random.
However it is useful for making dataframes with lists of test sequences if needed.

4. random_sequences.csv and random_sequences.pkl

These are the output files from Random Sequence Generator.ipynb
The pickle file can be put into Optimus 5 Prime, but you must make changes for it to accept the shape of the data.

5. training_MRL_CNN_test.hdf5

This is the actuall model saved from Optimus 5 Prime.
