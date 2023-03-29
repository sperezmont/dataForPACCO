
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

References (for data provided in this repo, orig/):

* Ahn-etal_2017:

Ahn, S., Khider, D., Lisiecki, L. E., & Lawrence, C. E. (2017). A probabilistic Pliocene–Pleistocene stack of benthic δ18O using a profile hidden Markov model. Dynamics and Statistics of the Climate System, 2(1).

* Barker-etal_2011:

Barker, S., Knorr, G., Edwards, R. L., Parrenin, F., Putnam, A. E., Skinner, L. C., ... & Ziegler, M. (2011). 800,000 years of abrupt climate variability. science, 334(6054), 347-351.

* Luthi-etal_2008:

Lüthi, D., Le Floch, M., Bereiter, B., Blunier, T., Barnola, J. M., Siegenthaler, U., ... & Stocker, T. F. (2008). High-resolution carbon dioxide concentration record 650,000–800,000 years before present. nature, 453(7193), 379-382.

* Snyder_2016:

Snyder, C. W. (2016). Evolution of global temperature over the past two million years. Nature, 538(7624), 226-228.

* Spratt-Lisiecki_2016:

Spratt, R. M., & Lisiecki, L. E. (2016). A Late Pleistocene sea level stack. Climate of the Past, 12(4), 1079-1092.

* Waelbroeck-etal_2002:

Waelbroeck, C., Labeyrie, L., Michel, E., Duplessy, J. C., Mcmanus, J. F., Lambeck, K., ... & Labracherie, M. (2002). Sea-level and deep water temperature changes derived from benthic foraminifera isotopic records. Quaternary science reviews, 21(1-3), 295-305.

* Hodell-etal_2023:

Hodell, David A; Crowhurst, Simon J; Lourens, Lucas Joost; Margari, Vasiliki; Nicolson, John; Rolfe, James E; Skinner, Luke C; Thomas, Nicola C; Tzedakis, Polychronis C; Mleneck-Vautravers, Maryline J; Wolff, Eric William (2023): Benthic and planktonic oxygen and carbon isotopes and XRF data at IODP Site U1385 and core MD01-2444 from 0 to 1.5 Ma. PANGAEA, https://doi.org/10.1594/PANGAEA.951401

