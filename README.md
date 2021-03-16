# EffectiveDurationGap

Computes the duration gap using the Effective Duration Formula for Assets and Liabilities.
INPUTS are:
Cashflows:dataframe with asset and liability cashflows labeled "Asset CFs" and "Liab CFs"
yields:   dataframe with columns \'Year\' and \'YC\' where \'YC\' represents base yields
delta_y:  value in decimal, e.g. 0.005 for 0.5%
