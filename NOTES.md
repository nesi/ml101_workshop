# Notes

One-off kernel to fix issues wrt ipywidgets

```
ml purge
module load JupyterLab
python3 -m venv --system-site-packages /nesi/project/nesi99991/ml101_20230509/venv
/nesi/project/nesi99991/ml101_20230509/venv/bin/pip3 install -U ipywidgets
nesi-add-kernel --shared --account nesi99991 --venv /nesi/project/nesi99991/ml101_20230509/venv \
    -- ml101_20230509 JupyterLab/2023.1.0-gimkl-2022a-3.5.3
```

To remove it later:

```
ml purge
module load JupyterLab
jupyter-kernelspec remove ml101_20230509
```
