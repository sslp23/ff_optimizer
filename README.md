# Fantasy Football Optimizer

The idea is to create an optimizer of Fantasy Football choices using ML. First I create the expected ppg model for each position, then I will optimize the choices base on the expected ppg.

Files overview:

- Data Download: download FF stats from Fantasy Pros
- Data Proccessing: uses the data to create basic variables
- Modelling - RBs: contains the analysis to develop the RBs model
- proj analysis: contains an analysis of the Fantasy Pros projected, in order to compare the quality of the expected ppg model
- Model Auto: notebook to automate the calculation of expected ppg for the 2023 season

Currently: creating code to optimal draft
