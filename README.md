# DeepUQ neurIPS ML4PS Paper 2024 
This repo demonstrates how to use the [DeepUQ](https://pypi.org/project/deepuq/) software to reproduce the results of the Nevin+2024 neurIPS workshop paper ["DeepUQ: Assessing the Aleatoric Uncertainties from two Deep Learning Methods"](https://arxiv.org/abs/2411.08587)


## How to reproduce the results of the paper
To exactly reproduce the results of the paper, run the two notebooks: `Train_DER_models.ipynb` and `Train_DE_models.ipynb`. The notebook will save the model checkpoints necessary to reproduce all figures and tables using the rest of the notebooks.

The config settings for the models used in the paper can also be found in `deepuq/utils/defaults.py` in the DeepUQ repo.


## Installation 
First, navigate to where you'd like to put this repo and type:
>git clone https://github.com/deepskies/DeepUQ-neurIPS-WS-2024.git

Then, cd into the repo:
>cd DeepUQ-neurIPS-WS-2024

Poetry is our recommended method of running a package environment as publishing and building is handled by a toml file that handles all possibly conflicting dependencies. Add poetry to your python install:
>pip install poetry

Then, from within the DeepUQ-neurIPS-WS-2024 repo, run the following:
>poetry install

Begin the environment:
>poetry shell

Now you have access to all the dependencies necessary to run the package.


## Citation 
```
@ARTICLE{2024arXiv241108587N,
       author = {{Nevin}, Rebecca and {{\'C}iprijanovi{\'c}}, Aleksandra and {Nord}, Brian D.},
        title = "{DeepUQ: Assessing the Aleatoric Uncertainties from two Deep Learning Methods}",
      journal = {arXiv e-prints},
     keywords = {Computer Science - Machine Learning, Computer Science - Artificial Intelligence},
         year = 2024,
        month = nov,
          eid = {arXiv:2411.08587},
        pages = {arXiv:2411.08587},
archivePrefix = {arXiv},
       eprint = {2411.08587},
 primaryClass = {cs.LG},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2024arXiv241108587N},
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}

```

## Acknowledgement 
We acknowledge the Deep Skies Lab as a community of multi-domain experts and collaborators who’ve facilitated an environment of open discussion, idea generation, and collaboration. This community was important for the development of this project. Work supported by the Fermi National Accelerator Laboratory, managed and operated by Fermi Research Alliance, LLC under Contract No. DE-AC02-07CH11359 with the U.S. Department of Energy. The U.S. Government retains and the publisher, by accepting the article for publication, acknowledges that the U.S. Government retains a non-exclusive, paid-up, irrevocable, world-wide license to publish or reproduce the published form of this manuscript, or allow others to do so, for U.S. Government purposes. This material is based upon work supported by the Department of Energy under grant No FNAL-LDRD- L2021-004.

### Author Contributions
Nevin: Conceptualization, Methodology, Formal analysis, Investigation, Writing - Original Draft, Writing - Review & Editing

Ćiprijanović: Conceptualization, Methodology, Formal analysis, Writing - Review & Editing, Supervision, Project administration

Nord: Conceptualization, Methodology, Formal analysis, Resources, Writing - Original Draft, Writing - Review & Editing, Supervision, Project administration, Funding acquisition

We thank the following colleagues for their insights and discussions during the development of this work: Sreevani Jarugula.
