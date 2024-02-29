# Addressing Deep Reinforcement Learning Empirical Algorithm Performance Evaluations

This repository contains the code used in my dissertation on deep RL evaluation methodologies. The dissertation is accompanied by a [publication](https://sites.google.com/view/marl-standard-protocol/) with Instadeep Ltd. titled:

**Towards a Standardised Performance Evaluation Protocol for Cooperative MARL**

R. Gorsane, O. Mahjoub, R. J. de Kock, R. Dubb, S. Singh, and A. Pretorius, “Towards a Standardised Performance Evaluation Protocol for Cooperative MARL,” in Thirty-Sixth Conference on Neural Information Processing Systems, 2022. [Online]. Available: https://openreview.net/forum?id=am86qcwErJm

## Contents of the Repo:

1. A Google Colab [notebook](EDA_RL_Evaluation_Literature.ipynb) for my analysis of a [dataset](https://drive.google.com/file/d/1XZXIEQU1zgq8nhROVukWnriCBRdUMtdO/view?usp=sharing) on deep cooperative MARL literature. Plots contained in section 2.3 of this dissertation are generated using this notebook.

2. A Google Colab [notebook](MCDA_textbook_plots.ipynb) for drawing the two plots of example preferential value functions found in subsetion 2.4 on multi-criteria decision analysis.

3. A Google Colab [notebook](Guideline_Data_Collection.ipynb) for the data collection phase recommended by our guideline for improved RL evaluation. This phase is elaborated on in section 4.1.1 of the dissertation.

4. RL algorithm performance data contained in this [folder](https://github.com/marlEvalDissertation/marlEvalDiss/tree/main/RL_data). The data is collected using this [notebook](Guideline_Data_Collection.ipynb) from 3. This folder also contains CSVs which are compiled and formatted by [notebook 5](Sample_Efficiency_Plots.ipynb) from the raw algorithm run output data.

5. A Google Colab [notebook](Sample_Efficiency_Plots.ipynb) for plotting the sample efficiency curves of the RL algorithms. These can be found in section 4.2 of the dissertation. This notebook also does the dataprocessing to convert the output from [notebook 3](Guideline_Data_Collection.ipynb) to CSV files.

6. A Google Colab [notebook](Guideline_Data_Aggregation.ipynb) for constructing and plotting partial value functions for each of the RL tasks in this dissertation. This notebook then conducts data aggregation of the RL runs using the partial value functions and chosen weights in order to compare RL algorithms. This is documented in section 4.1.4 and 4.1.5 of the dissertation. Results appear in section 4.2.

7. A Google Colab [notebook](Results_Analysis.ipynb) for analysing the algorithm performance results in terms of their robustness and sensitivity to changes.
