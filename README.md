This is a deep learning approach for protein prediction from single-cell RNA-sequencing data, where, over the model has 86% accuracy.


I split the training data( RNA and ADT) into 80-20 train-test split and trained the model with 80% training data which was later used to test with 20% of the remaining data. I calculated the loss by comparing the actual and predicted ADT(protein) from 20% test split. Finally, the model performance is compared and the model with maximum accuracy is used to predict protein from the actual test RNA.
