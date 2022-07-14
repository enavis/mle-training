# Median housing value prediction

The housing data can be downloaded from https://raw.githubusercontent.com/ageron/handson-ml/master/. The script has codes to download the data. We have modelled the median house value on given housing data. 

The following techniques have been used: 

 - Linear regression
 - Decision Tree
 - Random Forest

## Steps performed
 - We prepare and clean the data. We check and impute for missing values.
 - Features are generated and the variables are checked for correlation.
 - Multiple sampling techinuqies are evaluated. The data set is split into train and test.
 - All the above said modelling techniques are tried and evaluated. The final metric used to evaluate is mean squared error.

## To execute the script
Use the terminal or an Anaconda Prompt for the following steps:

1.Create the environment from the env.yml file: conda env create -f env.yml
2.Activate the new environment
3.Verify that the new environment was installed correctly: conda env list
4. Run the following command: python nonstandard.py

## Settings for VSCode 
{
    "workbench.colorTheme": "Default Light+",
    "python.defaultInterpreterPath": "C:\\Users\\emmanuel.navis\\Miniconda3\\python.exe",
    "editor.formatOnSave": true,
    "python.formatting.provider": "black",
    "python.formatting.blackArgs": [
        "--line-length = 88"
    ],
    "python.sortImports.args": [
        "--profile=black"
    ],
    "[python]": {
        "editor.codeActionsOnSave": {
            "source.organizeImports": true
        }
    },
    "editor.tabCompletion": "on",
    "python.linting.flake8Enabled": true,
    "python.linting.flake8Args": [
        "--max-line-length=88",
        "--ignore=E402",
    ],
    "files.trimTrailingWhitespace": true,
} 
