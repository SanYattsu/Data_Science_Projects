# Installation guide

```bash
# Update conda and install ds environment
conda update -n base -c defaults conda --yes
conda env create -f environment.yml

conda activate ds
conda deactivate
conda list -n ds

# .ps1 config
conda activate ds
function jlab{jupyter-lab --notebook-dir="~/git"}
```