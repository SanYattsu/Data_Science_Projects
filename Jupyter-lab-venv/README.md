# Installation guide

```bash
# Update conda and install ds environment
conda update -n base -c defaults conda --yes
conda env create -f environment.yml

# Add to shell to make ds default environment
conda activate ds

# Start jupyter-lab
jupyter-lab --notebook-dir=""

# Extra
conda deactivate
conda list -n ds
```