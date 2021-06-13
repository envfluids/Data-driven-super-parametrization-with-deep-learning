# Data-Driven Super-Parameterization Using Deep Learning: Experimentation With Multiscale Lorenz 96 Systems and Transfer Learning

To make weather and climate models computationally affordable, small-scale processes are usually represented in terms of the large-scale, explicitly resolved processes using physics-based/semi-empirical parameterization schemes. Another approach, computationally more demanding but often more accurate, is super-parameterization (SP). SP involves integrating the equations of small-scale processes on high-resolution grids embedded within the low-resolution grid of large-scale processes. Recently, studies have used machine learning (ML) to develop data-driven parameterization (DD-P) schemes. Here, we propose a new approach, data-driven SP (DD-SP), in which the equations of the small-scale processes are integrated data-drivenly (thus inexpensively) using ML methods such as recurrent neural networks. Employing multiscale Lorenz 96 systems as the testbed, we compare the cost and accuracy (in terms of both short-term prediction and long-term statistics) of parameterized low-resolution (PLR) SP, DD-P, and DD-SP models. We show that with the same computational cost, DD-SP substantially outperforms PLR and is more accurate than DD-P, particularly when scale separation is lacking. DD-SP is much cheaper than SP, yet its accuracy is the same in reproducing long-term statistics (climate prediction) and often comparable in short-term forecasting (weather prediction). We also investigate generalization: when models trained on data from one system are applied to a more chaotic system, we find that models often do not generalize, particularly when short-term prediction accuracies are examined. However, we show that transfer learning, which involves re-training the data-driven model with a small amount of data from the new system, significantly improves generalization. Potential applications of DD-SP and transfer learning in climate/weather modeling are discussed.

## Citation
- Chattopadhyay, A., Subel, A., & Hassanzadeh, P. (2020). Data-driven super-parameterization using deep learning: Experimentation with multiscale Lorenz 96 systems and transfer learning. Journal of Advances in Modeling Earth Systems, 12, e2020MS002084.([url](https://doi.org/10.1029/2020MS002084))<details><summary>BibTeX</summary><pre>
@article { Chattopadhyay_JAMES_2020,
  title={Data-Driven Super-Parameterization Using Deep Learning: Experimentation With Multiscale Lorenz 96 Systems and Transfer Learning},
  author={Chattopadhyay, Ashesh and Subel, Adam and Hassanzadeh, Pedram},
  journal={Journal of Advances in Modeling Earth Systems},
  volume={12},
  number={11},
  pages={e2020MS002084},
  year={2020},
  publisher={Wiley Online Library},
  url = "https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2020MS002084",
}</pre></details>
