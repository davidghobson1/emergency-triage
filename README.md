# Emergency Triage Project

This project explores the undertriaging of seniors in ML applications of emergency triage, specifically in predicting admission and discharge as done in Hong et al.

All models that have been trained for the project are included here, as well as the indices for the training and test sets for all experiments, so that results can be reproduced.

Our models confirm that accuracy is lower for seniors compared to adults (by about 4.5% absolute), even when trained on datasets with an equal number of seniors and adults. 

We've sought ways to remedy this. In particular, a basic comorbidity association graph has been created from full-text articles scraped from PubMed Central using a simple relation extraction framework. 

Preliminary experiments representing the complaint and past medical history features using pretrained biomedical NLP models has also been done. These embedding features have had no impact on accuracy up until this point however.
