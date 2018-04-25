## PS239T Final Project: Aging Immigrant Population by Legal Status (using CPS Data)

### Short Description

Drawing primarily form the Current Population Survey's (CPS) Annual Social and Economic Supplement (ASEC) for 2016 and 2017, this code provides the foundation for the preliminary analysis of the the data on older adults in the U.S. by legal status and gender. This data comes from from the University of Minnesota’s Integrated Public Use Microdata Series (IPUMS, https://cps.ipums.org/cps/).

The code is divided into **three** main sections.: (1) set up, (2) visualizations, and (3) machine learning. The *set up* section focuses on cleaning and creating the legal status variable using the CPS 2017 data. The *visualization* section plots and creates visualizations by legal status and age. The last section on *machine learning* provides code for using the clean CPS 2017 data to predict legal status.

#### Dependencies
  1. R, version 3.1.1.383
  2. LaTeX, MiKTeX 2.9 distribution.

### Files

#### Data:

Due to confidentially concerns, this data will not be uploaded. If you have any questions, please contact the researcher directly.

#### Code: 
  1. 01_setup.Rmd - cleaning and saving CPS 2017 data set; preparing CPS 2017 and CPS 2016 data for machine learning
  2. 02_visualizations.Rmd - plots and visualizations data by age, legal status, and gender
  3. 03_machine_learning.Rmd - basic machine learning decision tree for CPS 2016 data

#### Results: 
  1. binary_model.png - basic decision tree plot for CPS 2017
  2. decision_tree_output.png - image of most important variables for machine learning decision tree decision 
  3. g1_boxplot.png - 1 bloxplot showing older adults (50 + years old and older) by legal status
  4. olderadultsinUS.png - 3 plots showing older adults (50 + years old and older) by legal status and gender
  5. mexolderadultsinUS.png - 3 plots showing Mexican older adults (50 + years old and older) by legal status and gender

#### Presentation Files
This includes figures and results and other files needed to compile the final presentation.
  1. GarciaValdivia_Isabel_Presentation.tex - LaTeX presentation code
  2. GarciaValdivia_Isabel_Presentation.pdf - Presentation .pdf file
  3. Necessary Files for LaTeX Files
    1. GarciaValdivia_Isabel_Presentation.aux
    2. GarciaValdivia_Isabel_Presentation.log
    3. GarciaValdivia_Isabel_Presentation.nav
    4. GarciaValdivia_Isabel_Presentation.nav
    5. GarciaValdivia_Isabel_Presentation.snm
    6. GarciaValdivia_Isabel_Presentation.synctex.gz
    7. GarciaValdivia_Isabel_Presentation.toc
  4. Necessary image files for LaTeX Presentation
    1. g1_boxplot - 1 bloxplot showing older adults (50 + years old and older) by legal status
    2. g1_legalimmigrants - Legal immigrants older adults (50 + years old and older) by gender
    3. g2_undocimmigrants - Undocumented older adults (50 + years old and older) by gender
    4. g3_usborn - US-born older adults (50 + years old and older) by gender
    5. g4_usbornmex - US-born Mexican older adults (50 + years old and older) by gender
    6. g5_legalmex - Legal immigrants Mexican older adults (50 + years old and older) by gender
    7. g6_undocmex - Undocumented Mexican older adults (50 + years old and older) by legal gender
    8. decision_tree_output.png - image of most important variables for machine learning decision tree decision
    9. binary_model.png - image of basic decision tree plot for CPS 2017

#### **More Information**
For questions and/or concerns, please contact the creator.

**Creator:** Isabel García Valdivia (isabel.garcia@berkeley.edu)

**Course Instructor Spring 2018:** Rachel Bernhard (rbernhard@berkeley.edu)