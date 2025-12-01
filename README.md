# Deep Ensembles and Multisensor Data for Global LCZ Mapping: Insights from So2Sat LCZ42
Deep Ensembles and Multisensor Data for Global LCZ Mapping: Insights from So2Sat LCZ42

Attention! In the original version of the paper, the rows and columns in the confusion matrices are inverted. Here I have uploaded the PDF with the corrected confusion matrix.

Clearly, the batch size and the number of training epochs are closely related to your GPU computational power. 
Adjust them so that the training is feasible on your GPU.

We tested both SGD and Adam as optimizers and did not observe significant differences. Depending on the programming language or framework version you are using, 
we suggest testing both to see if you notice any variation. Remember not to use the official Validation Set, but rather to extract a validation subset from the Training Set 
to evaluate whether SGD or Adam performs better in your setup. Please refer to the paper for additional details on the Training/Validation/Test split.
