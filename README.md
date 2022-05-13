# Trends Marketplace
## Topic: Excel Operations in Jupyter Notebook using Mito

Mito is a spreadsheet that helps you complete your Python analyses 10x faster. You edit the Mitosheet, and it generates Python code for you. For more information click the
[Link](https://trymito.io/about)

Installation:
Check that you have Python 3.6 or above by opening a terminal and running `python --version`.

If required install Mito inside of a new virtual environment

Mito installation commands:
```
python -m pip install mitoinstaller
python -m mitoinstaller install
```
To create a Mitosheet, open a new or existing **JupyterLab** notebook. 

The common command to start JupyterLab is `python -m jupyter lab`

Use the below code for getting started
```
import mitosheet
mitosheet.sheet()
```

To Upgrade Mito 
open the terminal and virtual environment that you installed Mito on. 
Make sure you have the most up to date version of the mitoinstaller, by running the command:
```
python -m pip install mitoinstaller --upgrade
```

Now run the upgrade process:
```
python -m mitoinstaller upgrade
```
