# learning_python_conda

## Install package

`conda install numpy // package_name`

## Saving environments

`conda env export > environment.yaml`

## Loading environments

Load the previously created `environment.yaml` file via:

`conda env create -f environment.yaml`

## Remove environment

`conda env remove -n env_name`

## See installed packages

`conda list`

## Create `requirements.txt`

`pip freeze > requirements.txt`


