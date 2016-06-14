

# Project Objective:

This project applies an SVM based species distribution to model if solar installers have particular 'habits' (or preferred markets) which they work. We use household attributes from appraisal district data for the analysis. 

## in this repo
* `database.py` query database
* `make_bunches.py` - preprocess the data for future
* `installer_habitat_svm.py` contains data and script for analysis
* `filemanage.py`  load and save files in proper format


<!-- # Process
* Query database for 
* 
*  
* 
* 
*  -->



### dependencies
Scripts were written in Python 2.7. You'll need the following modules: 
```bash
matplotlib >= 1.5.1  
numpy >= 1.10.1  
pandas >= 0.17.1  
scipy >= 0.16.0
seaborn >= 0.6.0
sklearn >= 0.17
```

To install modules, run:  
```bash
$ pip install <module>
```

### running

## data sources/other credits
Thanks to: 
* Species distribution modelling http://scikit-learn.org/stable/auto_examples/applications/plot_species_distribution_modeling.html
* this was helpful for laying out  http://www.i-programmer.info/programming/python/3942-arrays-in-python.html?start=1
* and this for saving the grids http://geospatialpython.com/2013/12/python-and-elevation-data-ascii-grid.html