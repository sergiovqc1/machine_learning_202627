
```text
conda env create -f environment.yml
conda activate machine_learning_project
```

If the environment already exists and `environment.yml` has changed, update it:

```text
conda env update -f environment.yml --prune
```

### 4. Start Jupyter Notebook

```text
jupyter notebook
```