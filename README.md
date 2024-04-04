# Estimating 2019 General Election Results

The following analysis uses a Multi-level Regression and Post-Stratification (MRP) model to estimate UK General Election results in 2019. 

The files included in the repository are:
1. estimation_task_final.Rmd: R-Markdown file containing the data analysis and MRP modelling with report
2. estimation_task.html: HTML file for readibility
3. viz_task_final.ipynb: Jupyter notebook containing visualisation of vote estimates from MRP modelling
4. final_poststrat.csv: Final post-stratification frame, with scaled estimates

Datasets:
1. ons.csv: Custom dataset from ONS
2. bes2019.sav.zip: Zip file containing 2019 pre-election internet panel data (wave 17 of BES)
3. rps.sav: Random Probability Survey (post-election data from BES)
4. election-results.sav: 2019 Election Results downloaded from BES
5. party_wins.csv: Total predicted and actual wins by party
6. wins_by_con.csv: Wins by party with estimated and true vote shares
