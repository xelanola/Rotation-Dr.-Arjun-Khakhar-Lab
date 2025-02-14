1. Original Data Sets

These are tab delimited text files containing the original data provided by Dr. Greg Ebel.
Each data set has a list of SNPs and LPs that occur at different positions in the WNV genome.


Ref Pos: The position in the WNV genome where the mutation occurs.
Var: The mutation that occurred
Cons: The conserved/endogenous sequence at that position
strd_bias_pval: indicates the probability of seeing a strand bias
Type: SNP or LP
Var_Perc: frequency of counts where the position was the one observed in Var
SNP_or_LP_Profile: counts for all mutations observed by sequencing. #:# means sequenced positive strand: sequenced negative strand\

Each experiment was done in triplicate with three inputs, three infected birds, and 5 passages for each bird with the fifth passage also being done in triplicate.

In the original files the numbers at the end are identification numbers for the birds. 
AMCR=american crows
P1C=Passage 1 Replicate 3


2. CSV Data Sets

These contain the original data sets modified to a CSV format for easy readability.

For simplification of naming

Passage 5 triplicates were numbered in order matching the original data sets.

ex: P5A_R1=P5A_10 in the original data set
    P5B_R2=P5B_20 in the original data set

3. Sequence Lists

This is a list of WNV genome sequences representative of each data set.
Each sequence has the SNP or LP in it that is listed in CSV data sets.

4. CSV Data Sets with Sequences
   
This dataframe is a combination of CSV Data Sets and Sequence Lists.

The sequences with SNPs and LPs are lined up to the corresponding original data given by Dr. ebel

5. SNP_or_LP Sequence Generator.ipynb

This code takes the csv data sets and creates a new data base that looks like CSV Data Sets but with an additional column containing the WNV sequence with the respective SNP or LP. The output files are in CSV Data Sets with Sequences.
