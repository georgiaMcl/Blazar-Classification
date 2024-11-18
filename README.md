# Topics-in-computer-Science

The python code files are were used in the study: Random Forests in High-Energy Astrophyics

The goal of this project was to develop a machine learning algorithm, using the Random Forest model, to classify Blazar Candiates of Uncertain Type (BCUs) from the Fermi-LAT point source catalogues, into the two subclasses of blazars, BL Lacertae (BL Lacs) and Flat-Spectrum Radio Quasars (FSRQs).

The two catalogues analysed were the 3FGL (data from 2008 to 2012) and 4FGL-DR4 (data from 2008 to 2022) catalogues.

The random forest model was trained on 70% 3FGL BL Lac and FSRQ data, and tested against the remaining 30% BL Lac and FSRQ data.

Another random forest model was trained on 100% of the 3FGL BL Lac and FSRQ data, and tested against the 3FGL BCUs with 4FGL-DR4 BL Lac or FSRQ associations.

The files used to develop the model are described below: 

- The yml file, initialFermi.yaml, contains the details on the conda environemnt used to run the below python code files.

- InitialTesting: contains code and graphs created used to analyse the different features of the 3FGL catalogue. This was used to conduct pre-feature selection.

- fermiAnalysis: contains code on feature selection and hyperparameter tuning of the model for the 3FGL data set. This file also contains the random forest model evaluation on the 3FGL test set data.

- Compare4FGL: contains code on the 3FGL BCUs with 4FGL BL Lac or FSRQ assosiations evaluations and model performance.