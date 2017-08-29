# Synopsis
Script generates stats 
{Persent of Null, Dummy list, Persent of Null With Dummy, Type In Hive, Column Values, Column Size In MBytes}
for pyspark dataframe by partition (50mln records size in each) based on features list and saves result to xls file.

# Prerequisites
pyspark 2.1.0

# Usage
Set you feature list and XlsFile report name 
Get dummy list on one month and set it to DummyList var
Generate statistic to xls file in main cycle
