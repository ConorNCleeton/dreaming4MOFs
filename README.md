# dreaming4MOFs

<p align="center">
  <img src="./figures/dreaming.PNG" style="width: 50%;" />
</p>

This repo is intended as a documentation of the simulation experiments conducted in the scientific paper: [Design of metal-organic frameworks using deep dreaming approaches](https://chemrxiv.org/engage/chemrxiv/article-details/6628ea2721291e5d1d93a83e). 


Note:
-----
The scripts are provided as-is, and are not guaranteed to work without the required dependencies or with a different structure from that used in our work. If you have any questions, please contact the corresponding author of the article.

## 0. Dependencies

The code is primarily built upon the following libraries: `pytorch`, `numpy`, `pandas`, [selfies](https://github.com/aspuru-guzik-group/selfies.git), [group selfies](https://github.com/aspuru-guzik-group/group-selfies.git), `rdkit`, `scikit-learn`.

## 1. Training deep dreaming models

1.	To train a deep dreaming model, go to the directory `/train_models/` and run the `train_model.ipynb` jupyter notebook. It is recommended to train these models on a GPU. 
2.	Pre-trained deep dreaming models are available in the `/train_models/mof_saved_models/` directory.
3.	To visualise the parity plots for these models, run the `/train_models/plot_performance.ipynb` jupyter notebook. 


## 2. Deep dreaming experiments

1. Go to the `/deep_dreaming_experiments/` directory and explore the jupyter notebooks for the property case studies explored in the main article above (pore volume, $c_p$, and $Q_{CO_2}$ and $S_{CO_2/N_2}$).
2. Some of these studies rely on optimising seed distributions, which are contained in the `/deep_dreaming_experiments/seeds/` directory.
3. Deep dreaming results are stored in the `/dream_results/` subdirectory for each case study, and are visualised within their respective jupyter notebooks. 