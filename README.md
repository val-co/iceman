# Iceman: Fast Evasion Detection & Alert Management in Tree-Ensemble-Based Intrusion Detection Systems

This repository contains the code and experiments for the paper titled **"Fast Evasion Detection & Alert Management in Tree-Ensemble-Based Intrusion Detection Systems"** published in the *Proceedings of the IEEE 36th International Conference on Tools with Artificial Intelligence (ICTAI), 2024*.

## Dependencies

The following dependencies are required for this project:

- **[VoTE](https://github.com/john-tornblom/VoTE)** 
- **[VERITAS](https://github.com/laudv/veritas)** 
- **[Portion](https://pypi.org/project/portion/)** 
- **[GROOT Forests](https://github.com/tudelft-cda-lab/GROOT)** 
- **[OC-Score](https://github.com/laudv/ocscore)** 

Other dependencies include Pandas, Numpy, Tqdm, Functools, Scikit-Learn, XGBoost, Pickle, Plotly, Collections, and Imbalanced-Learn.

All the code is structured in the form of Jupyter Notebooks for ease of understanding and step-by-step execution, allowing you to experiment interactively.

Certain operations in the notebooks, such as the counterexample region generation process, can take up a fair bit of time (ranging from 30 to 150 minutes in our experiments). As a result, the final outcomes of these stages are saved as pickled objects in the repository. To re-run these experiments from scratch, simply comment out the code that loads the pickled objects.

For any questions, feel free to send me a message at **valency.colaco@liu.se**