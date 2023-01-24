The pymaceuticals program is built to analyze the results of 9 different drug regimens (and a placebo control group) for cancer drug trials. This program will merge multiple data tables and eliminate duplicated data and provide summary statistics for the various regimens.
The program produces several charts/tables for visualization:
    1- The number of total timepoints accumulated for each drug trial
    2- The split bwtween male and female mice tested
    3- Data on 4 promising drug trails: 'Capomulin', 'Ramicane', 'Infubinol', and 'Ceftamin'
        a- Determining IQR and bounds for outliers and listing any mice that qualify as outliers when comparing tumor volume at their final timepoint.
        b- Displaying that information in a combined box-and-whisker plot
    4- The tumor volume for a particular mouse in the Capomulin Trial across timepoints.
    5- Plotting the average tumor volume of mice in the Capomulin Regiment against the mouse weights and determing a correlation between the two using the Pearson Correlation Coefficient.