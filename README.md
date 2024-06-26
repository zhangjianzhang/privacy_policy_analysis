# Semantic Parsing of Data Practice Statements in Privacy Policies Using BERT Models

This repository includes all experiment materials for the paper *Semantic Parsing of Data Practice Statements in Privacy Policies Using BERT Models*

## Table of Contents

* Data: Privacy policy datasets used in our experiments;
* Codes: the python implementation of the automatic approach proposed by our paper;
* Results: the experiment results of data practice statements classification and semantic role instances annotation;
##  Model Files

The model files can be downloaded from Kaggle repository: https://www.kaggle.com/models/mrwh1tegive/privacy-policy-classify-1st-collection?select=model_tps_best.pth. These 4 models are used for privacy policy classification and semantic role labeling. 

- model_dr_best: classify data retention statements;
- model_fpc_best: classify first party collection statements.;
- model_tps_best: classify third party sharing statements;
- XML_model_srl: identify semantic role instances contained in the above three types of statements.
