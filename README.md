# Deep-RecSys-Explainability

This repositiory contains the development and implementation of methods defined in "DFEST: Feature Stability Descent & Tensor Search Explainability for Deep Recommendation Systems".

Synth_DFEST_vs_LIME.ipynb contains all methods demonstrated in the submitted manuscript for evaluating the explainability performance of DFEST & LIME against a synthetic ground truth model.


Secondary Files:

DeepFM-GDFTS.ipynb contains all methods to calculate instability of multi-way feature-interactions for any given recommendation predicted by a Deep Recommendation System, demonstrated here with a Deep Factorization Machine (DeepFM).

GD-FEST-Development.ipynb contains elements from development, as the basis for DeepFM-GDFTS.ipynb.

Embedding_inversion_generator.ipynb contains development for models to transform categorical feature values from embedding vectors of length k to one-hot encoding vectors of length m.
