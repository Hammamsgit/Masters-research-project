##############################INDEPENDENT RESEARCH PROJECT################################


The experiments have been placed in to two folders, one for the binary experiments, the second for multiclass experiments.
Generalisability experiments can be found in the multi-class folder/ in the results folder.

#Special care has been made to include a clear path link.
#where a path is found, please either update the path to match the path in the notebook,
e.g. /content/drive/MyDrive/RESEARCH-PROJECT/Multi_class_experiments
or modify */content/drive/MyDrive/* to match a similar path to where these experiments are performed.

These experiments have been conducted on google colaboratory. It is recommended that the recipient of these artefacts 
replicates this or uses a similar platform that supports the modules used, e.g. Tensorflow/Keras.

1. The binary experiments folder includes:

-a models folder containing 4 cGAN-RF models, one for each attack class.
-a datasets folder containing the prepared datasets needed for training and testing.
-a generated data folder for the user to save the best datasets ascertained.
-a generated models folder to house all the generated generator models as a result of cGAN-RF.

2. The multi-class experiments folder includes:

-a models folder containing the multi-cGAN-RF model.
-a datasets folder containing the prepared datasets needed for training and testing.
-a results folder housing the scores notebook. (This notebook is prepared with all of the results mentioned in the text, supplemented visually with graphs)
-a recommended generators folder (we have included the two best generators filtered from numerous tests, new_g_model_0128 generates the closest results to CICIDS2017,
 new_g_model_0130 generates closest datasets to CICIDS2018 )
-a generated data folder for the user to save the best datasets ascertained.
-a generated models folder to house all the generated generator models as a result of multi-cGAN-RF.