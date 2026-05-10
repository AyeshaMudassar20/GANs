GANS - Assignment 3
====================

Short description
-----------------

GANs assignment 3 — Jupyter notebooks with experiments and results for Generative Adversarial Networks (GANs).

About
-----

This repository contains the notebooks and supporting artifacts for Assignment 3 focusing on GANs. The notebooks demonstrate data preprocessing, model definitions, training loops, hyperparameter experiments, and visualization of generated samples and training metrics.

Included files
--------------

- `gen-ai-assignment-3-ques-01.ipynb` — Notebook for question 1, includes problem statement, approach, and results.
- `gen-ai-assignment-3.2.ipynb` — Main experiment notebook with model training and sample generation.
- `gen-assgnment-3.2.ipynb` — Duplicate/alternate notebook variant with other experiments or checkpoints.

Getting started
---------------

1. Clone the repository or download the files.
2. Create and activate a Python virtual environment (Windows example):

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

3. Install common dependencies (adjust versions as needed):

```powershell
pip install numpy matplotlib jupyterlab notebook torch torchvision tensorflow scikit-learn tqdm
```

4. Start JupyterLab or Jupyter Notebook and open the notebooks:

```powershell
jupyter lab
```

Notes
-----

- Hardware: Training GANs can be slow on CPU — a GPU with CUDA is recommended for full experiments.
- Data: If a notebook expects local datasets, ensure the dataset files are placed in the same folder or update the paths in the notebook.

Suggested workflow
------------------

1. Open `gen-ai-assignment-3-ques-01.ipynb` to review the task and approach.
2. Run `gen-ai-assignment-3.2.ipynb` (or the alternative `gen-assgnment-3.2.ipynb`) cell-by-cell, updating dataset paths if necessary.
3. Inspect generated images and logs; tweak hyperparameters and re-run training cells to reproduce experiments.

Acknowledgments
---------------

This work is part of an academic assignment on GANs. If you reuse or adapt parts of this repository, please cite any external sources or libraries used.

License
-------

No license specified. Add a LICENSE file (for example, MIT) if you want to grant reuse rights.

Contact
-------

Repository owner: AyeshaMudassar20
