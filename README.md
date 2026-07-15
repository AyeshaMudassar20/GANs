Generative Adversarial Networks — Image Synthesis
==================================================

Implementation and training experiments for Generative Adversarial Networks (GANs): data pipeline, model architecture, training loop, and generated-sample visualization.

About
-----

This repository contains notebooks demonstrating data preprocessing, model definitions, training loops, hyperparameter experiments, and visualization of generated samples and training metrics for GAN-based image synthesis.

Included files
--------------

- `gen-ai-assignment-3-ques-01.ipynb` — problem statement, approach, and results for the core GAN implementation.
- `gen-ai-assignment-3.2.ipynb` — main experiment notebook with model training and sample generation.
- `gen-assgnment-3.2.ipynb` — alternate experiment notebook with additional hyperparameter runs and checkpoints.

Getting started
----------------

Clone the repository or download the files.

Create and activate a Python virtual environment (Windows example):

    python -m venv .venv
    .\.venv\Scripts\Activate.ps1

Install common dependencies (adjust versions as needed):

    pip install numpy matplotlib jupyterlab notebook torch torchvision tensorflow scikit-learn tqdm

Start JupyterLab or Jupyter Notebook and open the notebooks:

    jupyter lab

Notes
-----

- Hardware: training GANs can be slow on CPU — a GPU with CUDA is recommended for full experiments.
- Data: if a notebook expects local datasets, ensure the dataset files are placed in the same folder or update the paths in the notebook.

Suggested workflow
-------------------

1. Open `gen-ai-assignment-3-ques-01.ipynb` to review the core GAN implementation and approach.
2. Run `gen-ai-assignment-3.2.ipynb` (or the alternate `gen-assgnment-3.2.ipynb`) cell-by-cell, updating dataset paths if necessary.
3. Inspect generated images and logs; tweak hyperparameters and re-run training cells to reproduce experiments.

License
-------

MIT License — see `LICENSE`.

Author
------

Ayesha Mudassar — [github.com/AyeshaMudassar20](https://github.com/AyeshaMudassar20)
