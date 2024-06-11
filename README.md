[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5711100.svg)](https://doi.org/10.5281/zenodo.5711100)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/valenpe7/5.0065167/master?urlpath=lab/tree/on_the_electromagnetic-electron_rings.ipynb)

# Ultrarelativistic electron beams accelerated by terawatt scalable kHz laser

This repository contains supplementary material for the work entitled "*Ultrarelativistic electron beams accelerated by terawatt scalable kHz laser*" that has been published in AIP **Physics of Plasmas** ([https://doi.org/10.1063/5.0189051](https://doi.org/10.1063/5.0189051)).

The supplementary material consists of the raw data computed by the **[EPOCH](https://cfsa-pmw.warwick.ac.uk/EPOCH)** code (v4.?) and the **[Jupyter](https://jupyter.org/)** notebook with the set of commands that have been used for developing the analytical model and generating the figures.

The analysis is performed using Python 3 programming language and relies on several Python packages: [numpy](https://github.com/numpy/numpy), [scipy](https://github.com/scipy/scipy), [matplotlib](https://github.com/matplotlib/matplotlib), and [sdf](https://github.com/keithbennett/SDF).

### How to obtain the data

The raw data used in this work are openly available in a **Zenodo** repository. You may download the data as a .zip archive (? GB) on the following link: https://zenodo.org/record/?.

### How to obtain the notebook

The notebook `analysis.ipynb` is stored in this GitHub repository. You may either download the whole repository as a .zip archive by selecting "Code" and then "Download ZIP", or use `git`:

1. Clone the repository: ``` $> git clone https://github.com/valenpe7/5.0189051.git ```
2. Pull in new changes: ``` $> git pull ```

### How to launch the notebook

If you have downloaded the notebook and the data and have all the requirements installed on your computer, you may launch the notebook locally. Alternatively, if you do not have installed all the requirements, you may launch the notebook on-line using
* **Jupyter NBViwever** (non-interactive): https://nbviewer.jupyter.org/github/valenpe7/5.0189051/blob/master/analysis.ipynb

* **Binder** (interactive): https://mybinder.org/v2/gh/valenpe7/5.0189051/master?urlpath=lab/tree/analysis.ipynb

### How to cite

Cite as: C. M. Lazzarini et al., *Phys. Plasmas* **31**, 030703 (2024).
```
@article{doi:10.1063/5.0065167,
        author = {Lazzarini, C. M. and Grittani, G. M. and Valenta, P. and Zymak, I. and Antipenkov, R. and Chaulagain, U. and Goncalves, L. V. N. and Grenfell, A. and Lamač, M. and Lorenz, S. and Nevrkla, M. and Špaček, A. and Šobr, V. and Szuba, W. and Bakule, P. and Korn, G. and Bulanov, S. V.},
        title = {Ultrarelativistic electron beams accelerated by terawatt scalable kHz laser},
        journal = {Physics of Plasmas},
        volume = {31},
        number = {3},
        pages = {030703},
        year = {2024},
        doi = {10.1063/5.0189051},
        URL = {https://doi.org/10.1063/5.0189051},
        eprint = {https://doi.org/10.1063/5.0189051}
}
```

### Acknowledgements

This work was supported by the project “ADONIS – Advanced research using high-intensity photons and particles” (No. CZ.02.1.01/0.0/0.0/16_019/0000789) from the European Regional Development Fund, by the “IMPULSE” project, which receives funding from the European Union Framework Programme for Research and Innovation Horizon 2020 under Grant Agreement No. 871161, and by the project “e-INFRA CZ” (No. ID:90254) from the Ministry of Education, Youth and Sports of the Czech Republic. The EPOCH code used in this work was in part funded by the UK EPSRC Grant Nos. EP/G054950/1, EP/G056803/1, EP/G055165/1, EP/M022463/1, and EP/P02212X/1.

---

In case of any questions, please contact the corresponding author or submit an **[issue](https://github.com/valenpe7/5.0189051/issues)** to this GitHub project repository.
