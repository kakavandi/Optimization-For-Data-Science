
# Hyperparameter optimization of deep neural networks with Pytorch and Ray Tune

In this project, students optimize hyperparameters of deep neural networks (DNN) on some popular benchmark datasets from [MoleculeNet](https://moleculenet.org/), including both classification and regression tasks. The target columns of each dataset are extracted from its corresponding MoleculeNet dataset. Also, 200 features containing global molecular information, extracted by [RDKit](https://www.rdkit.org/) package and CDF normalized by [Descriptastorus](https://github.com/bp-kelley/descriptastorus) package, are utilized as input features. In the following, some details about the benchmarks are provided.

## Classification Datasets
- **BBBP** (Blood-brain barrier penetration) dataset comes from a recent study on the modeling and prediction of barrier permeability. This dataset provides records of whether a compound is permeable to the blood-brain barrier. BBBP is a physiology dataset containing 2039 compounds.
- **ClinTox** dataset compares drugs approved by the FDA and drugs that have failed clinical trials for toxicity reasons. ClinTox is a physiology dataset containing 1478 compounds.
- **BACE** dataset provides binding results for a set of inhibitors of human β-secretase 1 (BACE-1) in the past few years. BACE is a biophysics dataset containing 1513 compounds.
- **HIV** dataset was introduced by the Drug Therapeutics Program (DTP) AIDS Antiviral Screen, which tested the ability to inhibit HIV replication for over some compounds. HIV is a biophysics dataset containing 41127 compounds.

## Regression Datasets
- **FreeSolv** is selected from the Free Solvation Database, which contains the hydration free energy of small molecules in water from both experiments and alchemical free energy calculations. FreeSolv is a physical chemistry dataset containing 642 compounds.
- **ESOL** is a small dataset consisting of water solubility data for some compounds. ESOL is a physical chemistry dataset containing 1128 compounds.
- **Lipophilicity** is a dataset which is curated from ChEMBL database. It is about an important feature of drug molecules that affects both membrane permeability and solubility. Lipophilicity is a physical chemistry dataset containing 4200 compounds.

## Students projects

| Name                      | Data      | GitHub Repository Link                                                                                                                                  |
| ------------------------- | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Sana Aria                 | ESOL      | [https://github.com/sanaaria/Hyperparameter-Optimization](https://github.com/sanaaria/Hyperparameter-Optimization)                                |
| Samira Moradzade          | BBBP      | [https://github.com/sanaaria/Hyperparameter-Optimizationn](https://github.com/sanaaria/Hyperparameter-Optimization)                               |
| Arash Sajjadi             | BBBP, HIV | [https://github.com/arashsajjadi/Hyper-parameter-optimization](https://github.com/arashsajjadi/Hyper-parameter-optimization)                      |
| Seyed Mahmoud Hashempour  | FreeSolv  | [https://github.com/Mahmoud4812/Hyperparameter-optimization--freesolv\_2](https://github.com/Mahmoud4812/Hyperparameter-optimization--freesolv_2) |
| Sajjad Sehatbakhsh        | ClinTox   | [https://github.com/sajjadsehat/Optimization-project.](https://github.com/sajjadsehat/Optimization-project.)                                      |
| Ahmad Yazdani             | Lipophilicity      | [https://github.com/mAbbaspour/Hyperparameter-Optimization](https://github.com/mAbbaspour/Hyperparameter-Optimization)                            |
| Mohammad javad Abbas pour | BACE      | [https://github.com/mAbbaspour/Hyperparameter-Optimization](https://github.com/mAbbaspour/Hyperparameter-Optimization)                            |

