
orig/		2023.02.13	Original files
co2/		2023.02.13	CO2 proxy netCDF files formatted as below
T/		2023.02.13	Air temperature anomalies netCDF files formatted as below
V/		2023.02.13	Volume (as sea level equivalent) netCDF files formatted as below
SST/	2023.02.15	Ocean temperature netCDF files formatted as below




## EVERY netCDF must contain ##
var, var_lo, var_up = variable, lower bound error, upper bound error

Names should be:
co2	-->	co2, co2_lo, co2_up
T	-->	T, T_lo, T_up
V	-->	V, V_lo, V_up


Note:
If original data has not error, set value -9999.0, NaN or missing value (plot and analysis purpose)

