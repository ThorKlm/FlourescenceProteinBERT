### FlourescenceProteinBERT ###
is a BERT-based model for the prediction of the excitation and emission wavelength of flourescence proteins and the application of interpretability.
Based on the pytorch implementation of ProteinBERT, that can be found at https://github.com/lucidrains/protein-bert-pytorch.


### Download links for the pretraining dataset and all model files ###
The compressed version of the Structural Protein Sequences-dataset, which was used for pretraining can be downloaded at https://seafile.cloud.uni-hannover.de/d/68f2c48225b442dc8306/.
All used models for the finetuning and interpretability experiments can be downloaded at https://seafile.cloud.uni-hannover.de/d/6d6625d67e494d54a00d/.
The "pretrained_sps_100.pt" containes the dictionary of the pretrained model.
For interpretability, the "pretrained_drp_0075_m_ex_em_2A.pt"-model is the finetuned ProteinBERT part and the "pretrained_drp_0075_b_ex_em_2A.pt" the corresponing wavelength prediction head resulting from finetuning of the pretrained model.
The "pretrained_drp_0075_m_ex_em_2B.pt" and "pretrained_drp_0075_b_ex_em_2B.pt" files are the corresponding results of the finetuning of the non-pretrained model.
