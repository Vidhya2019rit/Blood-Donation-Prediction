# Blood-Donation-Prediction
![image](https://user-images.githubusercontent.com/89641061/152186365-d3e81034-fd7f-4959-a220-ad2d08981d0f.png)
Blood Donation Data
![image](https://user-images.githubusercontent.com/89641061/152186660-00b48639-53ce-4e33-972b-386a289c5c56.png)
Resluts Data
![image](https://user-images.githubusercontent.com/89641061/152186788-bb77535d-da9e-4056-81ef-a6b23222c9ff.png)
Description
 Dataset was randomly partitioned into training set and testing set using a 70/30 train/test partition. Models are trained [3] using various algorithms using the entire training set, as well as trained on each cluster generated within the training set. Each model was trained once using what is referred to as a validation-set approach where there is one training set and one test set.

Once models are trained, the [5] test (i.e. holdout) data is fed into each trained model to measure [6] model performance. These measures allow us to gauge the generalizability of the remaining subset of data not used in the study, and provides us a feel to the degree of how overfit any models with respect to the training data.

The statistical performance measures we obtained were overall accuracy, sensitivity, specificity, and area under the curve (AUC). The overall accuracy measures how well you classify donors versus non-donors (TP+TN/Total). Sensitivity measures how well we are able to correctly predict donors whom have actually donated (TP/(TP+FN)). Specificity allows us to gauge how well we are able to predict non-donors among those whom did not donate (FP/(FP+TN)). AUC is generated from a receiver operating characteristic (ROC) curve.
