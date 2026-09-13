# Installation guide

```bash
# Init conda
source ~/miniconda3/bin/activate
conda init --all
conda tos accept --override-channels --channel https://repo.anaconda.com/pkgs/main \
&& conda tos accept --override-channels --channel https://repo.anaconda.com/pkgs/r

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