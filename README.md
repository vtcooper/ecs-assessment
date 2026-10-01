# ECS assessment

**TEMPORARY CODEBASE:** Note this codebase is a work-in-progress and is not yet designed for public use.

----------------------------------------------------------------------------

Bayesian assessment of equilibrium climate sensitivity (ECS) from process understanding, historical observations, and paleoclimate evidence.

**Option 1: Run quick tests in Google Colab:** click the badge link below to start running the notebook online. The first few cells of the ECS notebook install the required software automatically inside colab.

**ECS assessment:** This notebook computes the combined posteriors and likelihoods for each line of evidence. Run it using Google colab here with the following link, or skip below and follow the steps to download this repository and run your own version as a jupyter notebook.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vtcooper/ecs-assessment/blob/master/ecs_assess.ipynb)

**Cloud feedback assessment:** This notebook computes the total cloud feedback based on recent literature.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vtcooper/ecs-assessment/blob/master/cloud_assess.ipynb)

**Option 2: Run locally in Jupyter:** If planning to play with the code in more detail, clone this repository and run it in a jupyter notebook:

```bash
git clone https://github.com/vtcooper/ecs-assessment.git
cd ecs-assessment
conda env create -f ecs.yml
conda activate ecs
jupyter lab ecs_assess.ipynb
```

Use the Python kernel from the `ecs` environment and run the cells in order. Results are saved in `saved_results/`.
