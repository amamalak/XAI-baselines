# XAI-baselines

The notebook "Forced_Temp_train&explain_tf2" loads temperature data from the CESM2-LE, and then trains and explains a neural network (NN) that predicts the ensemble and global mean temperature given a global temperature map from individual members. The prediction task is chosen to be simple on purpose, since the focus here is to illustrate the importance and the effect of using different baselines when explaining NNs. 
The notebook "Forced_Temp_train&explain_tf2_DeepSHAP" is similar but uses Deep SHAP to explain the network. The notebook "Forced_Temp_train&explain_tf2_DeepSHAP_deepNN" trains a much deeper network. 
The CESM2-LE model output is publicly available online (https://www.cesm.ucar.edu/projects/community-projects/LENS2/data-sets.html).

Study: Mamalakis, A., E. A. Barnes and I. Ebert-Uphoff (2022) Carefully choose the baseline: Lessons learned from applying XAI attribution methods for regression tasks in geoscience, Artificial Intelligence for the Earth Systems. DOI: 10.1175/AIES-D-22-0058.1


