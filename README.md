# DFEST Feature Instability Search for Multi-Way Explainability of DNN

This repositiory contains the development and implementation of methods defined in "Feature Instability Search for Multi-Way Explainability". All development was performed in Jupyter Notebooks to allow for visualization of modular components of DFEST and the synthetic ground truth model.

Synth_DFEST_vs_LIME.ipynb contains all methods demonstrated in the submitted manuscript for evaluating the explainability performance of DFEST & LIME against the synthetic ground truth model.

LIME vs DFEST BCW Dataset.ipynb contains all methods used to generate figures 7 & 8 comparing the output of both DFEST and LIME on the Wisconsin Breast Cancer Dataset.


Secondary Files:

Synth_DFEST_V2.ipynb contains development for a local n-sphere based sythetic ground truth model as referenced in the paper conclusion.

DeepFM-GDFTS.ipynb contains all methods to calculate instability of multi-way feature-interactions for any given recommendation predicted by a Deep Recommendation System, demonstrated here with a Deep Factorization Machine (DeepFM).

GD-FEST-Development.ipynb contains elements from development, as the basis for DeepFM-GDFTS.ipynb.

Embedding_inversion_generator.ipynb contains development for models to transform categorical feature values from embedding vectors of length k to one-hot encoding vectors of length m.
