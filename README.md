## PS239T Final Project: Aging Immigrant Population by Legal Status (using CPS Data)

##Short Description
Drawing primarily form the Current Population Survey's (CPS) Annual Social and Economic Supplement (ASEC) for 2016 and 2017, this code provides the foundation for the preliminary analysis of the the data on older adults in the U.S. by legal status and gender. This data comes from from the University of Minnesota’s Integrated Public Use Microdata Series (IPUMS, https://cps.ipums.org/cps/).

The code is divided into **three** main sections.: (1) set up, (2) visualizations, and (3) machine learning. The *set up* section focuses on cleaning and creating the legal status variable using the 2017. The *visualization* section plots and creates visualizations by legal status and age. and the last section on *machine learning* provides code for using the clean 2017 CPS data to predict legal status.

##Dependencies
  1. R, version 3.1.1.383
  2. LaTeX, MiKTeX 2.9 distribution.

##Files

###Data:

Due to confidentially concerns, this data will not be uploaded. Please contact researcher for access to the data.

###Code: 
  1. 01_setup.Rmd - cleaning and saving CPS 2017 data set; preparing CPS 2017 and CPS 2016 data for machine learning
  2. 02_visualizations.Rmd - plots and visualizes data by age, legal status, and gender
  3. 03_machine_learning.Rmd - basic machine learning decision tree for CPS 2016 data

###Results: 
  1. binary_model.png - Basic decision tree plot for CPS 2017
  2. decision_tree_output.png - picture of most important variables for machine learning decision tree 
  3. g1_boxplot.png - 1 bloxplot showing older adults (50 + years old and older) by legal status
  4. olderadultsinUS.png - 3 plots showing older adults (50 + years old and older) by legal status and gender
  5. mexolderadultsinUS.png - 3 plots showing Mexican older adults (50 + years old and older) by legal status and gender

### Presentation Files
This includes figures and results and other files needed to compile the final presentation.
  1.
  2. 
  3.

##More Information 
For questions and/or concerns, please contact the creator.
>**Creator:** Isabel García Valdivia (isabel.garcia@berkeley.edu)
>**Course Instructor Spring 2018:** Rachel Bernhard (rbernhard@berkeley.edu)