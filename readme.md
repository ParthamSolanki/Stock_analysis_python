# Header

## Environment setup

### Creating environment

```Bash
mamba create -n <my_project_name> python=3.11 -y
mamba activate <project_name>
```

### Installing useful libraries

```Bash
mamba install yfinance
```

### Creating the requirements list

```Bash
mamba env create -f environment.yml
```
