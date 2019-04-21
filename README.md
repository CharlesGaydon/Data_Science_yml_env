# Data_Science_yaml_env
Basic yaml and instruction to start a new Data Science repository

Source : [Documentation for managing env in Anaconda](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#create-env-file-manually)

## Create an environment

    conda env create -f base_ml_env.yml

## Clone an environment

    conda create --name myclone --clone base_ml_env

## Activate & deactivate an environment

    conda activate myclone
    ...
    conda deactivate

## Export an environment into a yml file

    conda env myclone > myclone_env.yml
