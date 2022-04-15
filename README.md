# Scout_Energy_Coding_Challenge

Link to the repository - https://github.com/shivaram-abhishek/Scout_Coding_Challenge

This repository is created as a part of the Scout Energy's interview coding challenge.

The jupyter notebook takes an excel file as an input. The excel file contains the data along with id and timestamps.

### Part - 1
The code checks for the missing timestamps and adds them to the dataset, with all the other columns given a Null value. The code also handles missing timestamps where DST starts or ends for all timezones. The current set timezone is 'US/Central'. To change the timezone, update the given_tz variable in str_to_datetime() function.
A new column is created indicating the missing timestamps.

### Part-2
The code checks for the missing VTWS_AVG values. A new column is created to indicate the missing VTWS_AVG values.

### Results
The updated data is stored in a new excel file 'Result.xlsx'.
