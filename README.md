# Leveraging-Deep-Ensembles-and-Multisensor-Data-for-Global-LCZ-Mapping-Insights-from-So2Sat-LCZ42
Leveraging Deep Ensembles and Multisensor Data for Global LCZ Mapping: Insights from So2Sat LCZ42

Clearly, the batch size and the number of training epochs are closely related to your GPU computational power. 
Adjust them so that the training is feasible on your GPU.

We tested both SGD and Adam as optimizers and did not observe significant differences. Depending on the programming language or framework version you are using, 
we suggest testing both to see if you notice any variation. Remember not to use the official Validation Set, but rather to extract a validation subset from the Training Set 
to evaluate whether SGD or Adam performs better in your setup. Please refer to the paper for additional details on the Training/Validation/Test split.
