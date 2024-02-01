# 2D-<sup>1</sup> H - <sup>13</sup> C Heteronuclear Single Quantum Coherence Nuclear Magnetic Resonance (HSQC-NMR) fitting 

"Quantification of native lignin structural features with gel-phase 2D-<sup>1</sup> H - <sup>13</sup> C Heteronuclear Single Quantum Coherence Nuclear Magnetic Resonance (HSQC-NMR) reveals lignin structural changes during extraction"
[![arXiv](https://img.shields.io/badge/arXiv-2312.13136-b31b1b.svg)](https://arxiv.org/abs/2312.13136) ajouter le link publi ici

![Fig 1](./Fig_1.png)

Reliable integration is required blablabla... 

![mhnn-method](./mhnn.jpg)

## 📌 Pre-requisite: data conversion
Each HSQC NMR spectra has to be converted into three text matrices specifying the lists of <sup>1</sup> H chemical shifts, <sup>13</sup> C chemical shifts, and 2D intensities using the [rbnmr](https://www.ibbr.umd.edu/nmrpipe/install.html)  Matlab function developed by Bruker. 
Alternatively, [NMR Pipe](https://www.ibbr.umd.edu/nmrpipe/install.html), a UNIX spectra processing system, can be used to perform this operation. 


## 🚀 Environment Setup

- We'll use `conda` to install dependencies and set up the environment.
We recommend using the [Python 3.9 Miniconda installer](https://docs.conda.io/en/latest/miniconda.html#linux-installers).
- After installing `conda`, install [`mamba`](https://mamba.readthedocs.io/en/latest/) to the base environment. `mamba` is a faster, drop-in replacement for `conda`:
    ```bash
    conda install mamba -n base -c conda-forge
    ```
- Create a new environment named `mhnn` and install dependencies.
    ```bash
    mamba env create -f env.yml
    ```
- Activate the conda environment with `conda activate mhnn`.

## 💿 Spectra database
In the [Data folder](https://pages.github.com/mettre lien github folder),  you can find examples of raw NMR datasets, translated into text files and further analyzed using the algorithm.
Both soluble lignins and whole cell walls samples have been shared.

## 🌈 Acknowledgements
This work was supported as part of NCCR Catalysis (grant number 180544), a National Centre of Competence in Research funded by the Swiss National Science Foundation.

## 📝 Citation
If you find our work useful, please consider citing it:
```bibtex
@article{,
  author    = {},
  title     = {},
  journal   = {},
  volume    = {},
  year      = {2024},
  url       = {https://}
}
```

## 📫 Contact
If you have any question, welcome to contact me at:
Claire Bourmaud - claire.bourmaud@epfl.ch
