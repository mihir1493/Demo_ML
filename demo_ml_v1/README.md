# Demo_ML
Creating a repo for storing and testing end to end deployment scripts


### Creating a Data Science - Standard Template 
[YTLink](https://www.youtube.com/watch?v=mpk4Q5feWaw)
[Article](https://clickup.pxf.io/ana61R)

* pip install cookiecutter-data-science
* ccds 

Create virtual environment 
* conda create -n myenv python=3.10
* conda activate myenv
* conda install --yes --file requirements.txt


### Transform Jupyter Notebook to Packaged Production Code 
`- Why do we make package - Idea is to embedd the model as a dependency in application that makes it easy to consume.`   
STD Conventions -> Versioning | Config | PEP8/linting tools
Package Mandatory Files -> setup.py & MANIFEST
