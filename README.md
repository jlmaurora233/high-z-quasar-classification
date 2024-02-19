# high-z-quasar-classification project <br>
For files corresponding to the folder `rf_model_results`:<br>
The goal is to develop one or more efficient and accurate machine learning model(s) to classify quasars with SDSS's Legacy Survey data. After attempting on different classifiers (*not* included in this folder), the models selected are random forest classifier and kNN. The Random Forest model trained on magnitude is very effective in classifying the target with an average training accuracy score of 0.95, and both test precision and recall rates are around 0.9 (when the test data strictly follows the same processing steps as the training data does). The kNN model is more of a complementary one. <br>
*Note*: the attempts, including some of the test files and steps, are missing because of some storage disk issue with the local computer.<br>

For files corresponding to the folder `knn_model_results`: <br>
The goal of this project is to find a more effective classification criteria that tells high-redshift quasars (bright cores of distant galaxies; they encode information about galaxy formation and evolution) apart from brown dwarfs and low-redshift galaxies. The features used are photometric magnitude differences (aka 'colors'). <br>
Above is a collection of the code of the high-redshift quasar classification project. Those start with `decision boundary` include the data cleaning and training processes. Those with `pipeline` include the selection and combination of KNN models and the tests on their performances. <br>
See `KNN Classification on High Redshift Quasars.pptx` for more details on the project overview and model performance.
