# Flood Exposure-Coping Strategies-Psychological Distress

About the project

This repository contains the R script used to examine how long houses stayed under flood water. It also examines which coping strategies households used. Finally, it examines how much psychological distress households reported.
. The figure looks at 

Study area: 
Sunamganj and Sylhet, Bangladesh


The analysis answers two questions:

1. Is psychological distress linked to the number of days a house stayed under water?
2. Do households that used a coping strategy report different distress scores from households that did not?

Data

The script reads the survey file Data_Final.sav. It is not included in this repository because it contains survey data. Put the data file in the same folder as the script before you run it.

What the script does
a. Cleans and recodes the survey variables.
b. Builds an 11-item distress score and rescales it to 0–100.
c. Groups flood duration into bands.
d. Runs Spearman rank correlations.
e. Compares distress scores across coping strategies with the Wilcoxon rank-sum test.
f. Adjusts p-values with the Holm method.
g. Hides any group with fewer than 10 respondents.
h. Saves the figure, summary tables and an analysis log.

Requirements
R (4.1 or later recommended)


Font: Times New Roman (the script uses it for all text in the figure)
Install the packages once:
haven
dplyr
ggplot2
patchwork
ragg
