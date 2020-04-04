# ncov-ligand-protein
ncov-ligand-protein: A collection of models trained for predicting activity across molecular assays for the 3clpro protease in SARS-CoV-2. 

The repo currently consists primarily of Random Forest models trained and evaluated on molecular assays for the 3cl-pro protease of SARS-CoV-1, which is believed to be highly homologous to the 3cl-pro protease in SARS-CoV-2 (96% structural similarity). The models are trained on Morgan fingerprints of molecular assays provided by the MIT J-Clinic (https://www.aicures.mit.edu/data). 

Todo:
- Start work on graph model-based approaches. 
- Apply DeepChem hyperparameter optimization to Random Forests
- Developing some kind of protein crystal-structure representation (this will probably be hard to achieve without calculating free binding energies of molecule confirmations, so its TBD).
- Possible future approach: XGBoost gradient boosting trees.
