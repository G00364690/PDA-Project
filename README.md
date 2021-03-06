# Simulate a Real World Phenomenon

This assignment has been completed in accordance with the tasks set out in the coursework of the Fundamentals of Data Analysis module as part of the Higher Diploma in Data Analytics in Galway-Mayo Institute of Technology.

Assignment completed by:
Declan Reidy - December 2018


## Instructions
In order to complete this assigment it was necessary to:
1. Download & install Anaconda
2. Download & install Console Emulator x64
3. Create directory and files such as this README, LICENSE and .gitignore using Linux commands
4. Launch a jupyter notebook from the command line and create PDA-Project.ipynb
5. Download the Anscombe Quartet dataset and read the dataset into PDA-Project.ipynb and perform analysis
6. Sync files on my local machine to repository on GitHub allow me to push/pull updates to the jupyter notebook over various commits

To review the analysis methods and conclusions from the assigment:
1. Simply launch the Jupyter Notebook entitled "PDA-Project.ipynb"
2. Review the full analysis in the Jupyter Notebook
3. Run individual elements of the python code by highlighting cells and using command SHIFT+ENTER
4. Consult the "Objectives" section of this README file for information on the objectives and structure of this assignment
5. Consult the "Initial Research" section of this README file for information on my approach to this assignment
6. Consult the "Method" section of this README file for information on my methodology for this assignment
7. Consult the "References & Research" section of this README file for information on my further reading in relation to this assigment

## Objectives
The aim of this project is to:
1. Summarise a real world problem of interest to me
2. Derive project plan
3. Initial Research
4. Method
5. References & Research

## Summary of real world phenomenon
The real world phenomenon I want to simulate is expected goals. In order to simulate expected goals we need to break down the parameters and variables that comprise the expected goals model. If these variables prove too elaborate to simulate we can derive our own expected goals model from simpler variables with more measurable distributions.

## Plan the project
The approach to this project has been to:

1. Decide on the real life phenomenon to simulate
2. Investigate the variables driving the phenomenon and simplify the problem to most dominant variables
3. Investigate dominant variables and determine their average value ranges and distributions
4. Write some python code to display the data
5. Simulate the phenomenon and with sythesized data

## Initial research
Initial research of the phenomenon indicated that the variables that comprise the expected goals model were quite complex to find sample data for and thus challenging to simulate. 

1. Header
2. Distance to goal
3. Visible angle of the goal
4. Big chance

The method by which we simulate expected goals would need to be derived from simpler parameters. 

1. Distance to goal
2. Shots
3. Shots on target
4. Goals

## Method
Research indicated that 

1. Distance to goal
2. Shots - Some research would indicate there are between 20 and 40 shots in a game. (between 10 and 20 per team)
3. Shots on target - Some research would indicate there are between 10 and 15 shots on target in a game. (between 3 and 8 per team)
4. Goals - Looking to existing data we'll make the assumption that there is an average of 2.5 goals per game in a top level game.


## References & Research
https://towardsdatascience.com/histograms-and-density-plots-in-python-f6bda88f5ac0
https://seaborn.pydata.org/generated/seaborn.distplot.html
https://medium.com/@gis10kwo/plot-histogram-and-probability-density-function-pdf-in-matplotlib-python-4577a063e56c
https://stackoverflow.com/questions/4150171/how-to-create-a-density-plot-in-matplotlib
https://python-graph-gallery.com/density-plot/
https://het.as.utexas.edu/HET/Software/Numpy/reference/routines.random.html
https://www.pinnacle.com/en/betting-articles/Soccer/how-to-calculate-poisson-distribution/MD62MLXUMKMXZ6A8
http://www.physik.uni-leipzig.de/~janke/CompPhys06/Folien/Nussbaumer.pdf
https://help.smarkets.com/hc/en-gb/articles/115001457989-How-to-calculate-Poisson-distribution-for-football-betting
https://dashee87.github.io/football/python/predicting-football-results-with-statistical-modelling/
https://warwick.ac.uk/fac/sci/physics/research/cfsa/people/sandrac/publications/footy.pdf
https://www.sportskeeda.com/football/team-focus-the-correlation-between-shots-per-game-and-goals-scored
https://www.pinnacle.com/en/betting-articles/Soccer/how-to-calculate-expected-goals-for-soccer-matches/JESJH3RKXCMUF9TY
https://cartilagefreecaptain.sbnation.com/2015/10/19/9295905/premier-league-projections-and-new-expected-goals
http://www.football-bookmakers.com/news/shoot-why-shots-on-target-ratios-are-the-only-stat-you-need.html
http://www.soccerstatistically.com/blog/2011/7/18/do-shots-on-goal-matter.html
https://cartilagefreecaptain.sbnation.com/2014/2/28/5452786/shot-matrix-tottenham-hotspur-stats-analysis-expected-goals
http://www.footcharts.co.uk/index.cfm?task=corr_attack&league=E0&venue=T&season=20/12/2018
