# This is an instructional file for the thesis on Machine Learning Methods to Predict Queen Bee Acceptance and Presence.
# Please read through this document to understand the order in which the syntax is to be executed for replication.

#Storage & Working Directory
1. All scripts are to be stored in a subfolder called '/Scripts' within a main folder called 'Honey Bee'
2. All backups are to be stored in a subfolder called '/Backups' within a main folder called 'Honey Bee'
3. The Quarto file needs to be stored in a subfoler called '/Quarto' within the main folder called 'Honey 'Honey Bee'
4. The main folder 'Honey Bee' is to be set as the working directory for all python scripts
5. The subfolder 'Quarto' is to be set as the working directory for all QMD and R related files.

#Required Software:
1. Python 3.11.3- https://www.python.org/downloads/
2. R- https://cran.r-project.org/bin/windows/base/
3. Spyder IDE: https://www.spyder-ide.org
4. R Studio: https://posit.co/download/rstudio-desktop/
5. Anaconda: https://www.anaconda.com/download

Required Data: https://www.kaggle.com/datasets/annajyang/beehive-sounds

#Construction of conda environment:
1. A conda environment is to be created by the name of 'spyder' and is to be set up in the working directory of the spyder IDE
2. The following packages are need to be installed for the scripts in the project to work
   - numpy
   - pandas
   - sklearn
   - PIL
   - gc
   - os
   - matplotlib
   - plotnine
   - xgboost
   - seaborn
   - cv2
   - umap
   - tensorflow (recommended along with all add-ons)

#Please note that some of these libraries may come preinstalled along with Python installation.
#All of these libraries can be installed onto the environment 'spyder' using either Anaconda graphical interface or conda command line.

#Syntax to install libraries using conda command line
1. conda activate spyder
2. conda install -c conda-forge <package>

Alternatively syntaxes that may be entered after activating conda environment:
1. conda install <package>
2. pip install <packages>

#Commands to start Spyder using specific enviroment (to be inputted within Anaconda command line)
1. conda activate spyder #This activates the environment named Spyder
2. spyder #This starts Spyder IDE
(In the prompts above, do not input the comments added after the # symbol)

#The scripts in the Honey Bee project are to be executed in this order:
1. Data Wrangling.py
2. Basic Visualisation.py
3. UMAP.py
4. Support Vector Machine.py
5. Random Forest.py
6. Gradient Boosting.py
7. CNN.py
('Pickle Backup.py' only stores a function to simplify creating and updating pickle archive files. It need not be executed specially as it has been executed separately in other files.)

#The QMD file can be opened directly in R Studio.

#Libraries required for running QMD file:
1. reticlulate (EXTREMELY IMPORTANT TO RUN PYTHON SYNTAX IN R)
2. knitr

#In each of the scripts, file locations have been set based on how the files have been stored in my PC, however, there may be a case wise need to edit the file locations as needed. They may differ in every computer, and hence, it is important to check and edit the locations referenced in each script as required.
