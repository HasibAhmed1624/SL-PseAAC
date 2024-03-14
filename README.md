# StackDPP
In this work
  1. We have proposed a new dataset for DNA binding protein (DNA-BP) prediction. The training dataset (UNIPROT1424) is available in uniprot1424.fasta. The independent test set (UNIPROT356) is available in uniprot356.fasta.
  2. We have proposed a stacking ensemble model for DNA-BP prediction. We have named this predictor StackDPP.
 
The resources attached to this repository are as follows:
  1. DataSet: This folder contains the datasets used in this work. pdb1075.fasta, pdb1035.fasta, pdb186.fasta are datasets from previous work and uniprot1424.fasta, uniprot356.fasta are the proposed new benchmark datasets.
  2. Features: This folder contains the finally selected features for StackDPP.
  3. Results: The results of some of our experiments are placed under this folder as CSV files. All the experimental results are available in the manuscript.
  4. Scripts: Run the script in the script folder to generate results. Both the notebook version and Python script execute the same logic.
     
 ## Run the predictor on your protein sequences
  1. We will need the sequence, PSSM, and Spider output of the sequence. Two example files, example.pssm and example.spd33 have been uploaded.
  2. Run the TestANewSequence script (either Python script or notebook version) by setting up the variables (sequence, pssmFile, spiderFile).


