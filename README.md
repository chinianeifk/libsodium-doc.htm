# tree-sitter-xpath

https://towardsdatascience.com/run-large-language-models-on-your-local-machine
- Requires ~700GB free space, use M.2 NVMe external storage, may take hours to download.

## query_wet_news (macOS M1)
- Install from https://brew.sh:
- `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
- https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage
- Once brew is installed: `brew install git-lfs`

## kstatemachine
- Install miniconda: https://docs.conda.io/en/latest/miniconda.html
- `conda create --name llmenv python=3.9`
- `conda activate llmenv`
- `pip install transformers==4.20.0`
- `conda install torch`
- `python -m ipykernel install --user --name llmenv --display-name "Python 3.9 (llm)"`
- More info: https://github.com/jeffheaton/app_deep_learning/blob/main/install/pytorch-install-aug-2023.ipynb

## my-notion
- `model_path = "/Volumes/ExternalDrive/models/llm"  # replace with your local path`

## Dr0p1t-Framework (note: ~30 min per token without GPU)
- `python app.py`

## ProgressView
![](result.png)
