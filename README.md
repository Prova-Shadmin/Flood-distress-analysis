# Flood Exposure-Coping Strategies-Psychological Distress

Study area: Sunamganj and Sylhet, Bangladesh
Survey year: 2022

About this project

This repository contains the R script used to make Figure 3. The figure looks at how long houses stayed under flood water, which coping strategies households used, and how much psychological distress they reported.

The analysis answers two questions:

1. Is psychological distress linked to the number of days a house stayed under water?
2. Do households that used a coping strategy report different distress scores from households that did not?

Data

The script reads the survey file Data_Final.sav. The file is not included in this repository because it contains survey data from respondents.

Put the file in the same folder as the script before you run it.

What the script does
Cleans and recodes the survey variables.
Builds an 11-item distress score and rescales it to 0–100.
Groups flood duration into bands.
Runs Spearman rank correlations.
Compares distress scores across coping strategies with the Wilcoxon rank-sum test.
Adjusts p-values with the Holm method.
Hides any group with fewer than 10 respondents.
Saves the figure, summary tables and an analysis log.
Requirements

Install the packages once:
