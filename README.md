# dreaming4MOFs

<p align="center">
  <img src="./figures/dreaming.PNG" style="width: 50%;" />
</p>

This repo is intended as a documentation of the simulation experiments conducted in the scientific paper: [Design of metal-organic frameworks using deep dreaming approaches](https://chemrxiv.org/engage/chemrxiv/article-details/6628ea2721291e5d1d93a83e). 


Note:
-----
The scripts are provided as-is, and are not guaranteed to work without the required dependencies or with different structure from that used in our work. If you have any questions, please contact the corresponding author of the article.

## 0. Dependencies

The code is primarily built upon the following libraries: `pytorch`, `numpy`, `pandas`, [selfies](https://github.com/aspuru-guzik-group/selfies.git), [group selfies](https://github.com/aspuru-guzik-group/group-selfies.git), `rdkit`, `scikit-learn`.

## 1. Training deep dreaming models

1.	To train a deep dreaming model, go to the directory `/train_models/` and run the `train_model.ipynb` jupyter notebook. It is recommended to train these models on a GPU. 
2.	Pre-trained deep dreaming models are available in the `/train_models/mof_saved_models/` directory.
3.	To visualise the parity plots for these models, run the `/train_models/plot_performance.ipynb` jupyter notebook. 


