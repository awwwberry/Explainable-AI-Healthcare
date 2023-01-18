# Explainable-AI-Healthcare

Improve accuracy of an explainable AI model’s prediction of patient outcomes by adding stacked generalization

Project by Aubrey Moulton, Abdullah Aman Tutul, Edmund Do
Department of Computer Science and Engineering, Texas A&M University

In this project we aim to improve the accuracy of the explainable AI (XAI) model’s prediction by adding stacked generalization. In this study we analyze patient data from a hospital intensive care unit (ICU). Our goal is to predict the patient's mortality while in the ICU. Stacked generalization has two layers. The first layer, the base learner, is an explainable boosting machine (EBM). Training data is inputted into the EBM and the output is feature importance scores for every feature. The second layer, the meta learner, is a machine learning classifier. The feature importance scores are used to train the meta learner. Our hypothesis is that the meta learner will be more expressive if we use feature importance values from EBM to train the meta learner. These results are significant because the results will be both explainable and more accurate. This proposed pipeline will be an excellent tool for doctors to understand the results and also have higher accuracy.
