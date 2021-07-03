# TagRec_EMCL_PKDD_2021

This repository contains the code for our paper TagRec: Automated Tagging of Questions withHierarchical Learning Taxonomy  accepted to ECML-PKDD 2021

The notebooks are provided for easy training and inference for the users. Please contact venkteshv@iiitd.ac.in if you ahve any difficulty in running or 
reproducing the results. Please provide 5 working days at max for response.

The following provide an idea of the notebooks and associated methods. <br />
<b> ARC_Tagrec_BERT_SENT_BERT.ipynb </b> - TagRec method on ARC dataset, training and inference code (marked by section titles in notebook) (BERT + SENT_BERT) <br />

<b> ARC_dataset_Tagrec_BERT_USE_final.ipynb </b> - TagRec method on ARC dataset, training and inference code (marked by section titles in notebook) (BERT + USE)
<br />

ARC_euclidean_taxonomy_prediction_glove.ipynb - Baseline which uses BERT to encode QA pairs and Glove to encode labels <br />

ARC_euclidean_taxonomy_prediction_twin_BERT.ipynb - Baseline which uses two BERT models one for QA pair and another for label following the work of https://arxiv.org/abs/2002.06275 <br />


data <br />
   ├── targets_ARC.csv - Targets for Arc data for retrieval at inference <br />
   ├── train_QC_data.csv - ARC train dataset (the QC in filename has no relation to the other dataset in paper <br />
   ├── test_QC_data.csv <br />
   ├── val_QC_data.csv <br />
   └── what_you_learnt_lo_labelled.csv -  Learning objectives data to test zero shot abilities <br />
   
   The QC_science datset will be made available on demand <br />
<b> A service with inference API coming soon in this repo </b>
