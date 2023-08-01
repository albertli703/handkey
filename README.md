# handkey

Read a csv file and create a excel file for each subcontractor company, 

Issue
1) The 'Monthly Employee Report' does not show the total number of worker employed in the month related to the subcontractor company
2) The 'in time' and 'out time' of a worker are presented in the same row (~30 columns for in time and ~30 columns for out time) and it is difficult to counter check and calculate overtime or allocate time spent on specific day for specific purpose.
3) The 'total working days' in the report is distorted when the worker forgot to either tag in or tag out

Solution 
1) create list of workers (Sheet 'list of workers'),
2) create list of in time and out time, one row for one labour one date (Sheet 'in out time'),
3) create a summary table for the worker present on site, a worker is considered present if he has tagged either in or out (Sheet 'summary').
