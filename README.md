# Green hydrothermal synthesis of 2,3-diarylquinoxalines and large-scale computational comparison to existing alternatives
## Study authors
Fabián Amaya-García, Michael Caldera, Anna Ringler, Stefan Kubicek, Jörg Menche, and Miriam M. Unterlass

Correspondence to: Miriam Unterlass miriamunterlass@gmail.com
## Summary
Code used for the computational part of the study "Green hydrothermal synthesis of 2,3-diarylquinoxalines and large-scale computational comparison to existing alternatives" by Amaya-García et al. 
## Data availability
All data and code needed to reproduce the analysis and plots regarding the computational part of this study can be found within the /data folder of this github repository
## Structure
code/ contains all jupyter notebooks used for the analysis in this study  
data/raw/ contains the original raw data used in this study  
data/processed/ cotains the data after processing it (using 2_Prepare_Input_Files.ipynb)  
results/ contains all the result files (can be created using: 3_Make_Spiderplots.ipynb; 4_GeneralAnalysis.ipynb)  
## Installation and system requirements
Python packages used for analysis  
All code written for this program was in python 3.7.2  

Python version: 3.7.2  
Python packages included:  
numpy [v 1.16.0]  
scipy [v 1.2.0]  
pandas [v 0.24.0]  
sklearn [v 0.20.3]  
matplotlib [v 3.0.2]  
seaborn [0.9.0]  
umap [0.3.10]
### System requirements
Code was written and execuded on a MacBookPro  

CPU: Intel Core i5  
Memory: 8GB  
Graphics: Intel Iris Graphics 6100  
MacOS: 10.14.3  
### Installation instructions
All python packages should be easily being installed via pip [https://pypi.org/project/pip/]  
e.g. pip install <package_name>  
Typically time to install all packages should be less than 30min depending on the amount of previously installed packages.
### Code execution time
Running all three notebooks should take less than 15min (given the same or a similar system)
