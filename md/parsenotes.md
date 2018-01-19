#### Hydrograph parsing

This algorithm is used to parse the hydrograph into three main constituents:

1.	The rising limb (qtyp code 4) – the rapid increase in discharge following a storm/melt event;
2.	The falling limb (qtyp code 1) – the rapid decrease in discharge following the rising limb; and,
3.	Streamflow recession (qtyp code 2) – the gradual decline in discharge as the watershed drains.

Event volumes are calculated using an algorithm that locates the onset of a rising limb and projects streamflow recession as if the event had never occurred. This projected streamflow, termed "underlying flow" by Reed et.al. (1975), is subtracted from the total observed flow to approximate the runoff volume associated with the event as indicated by the hydrograph. The calculation of event volumes, in effect, "discretizes" the continuous hydrograph such that it can be better compared with measured (i.e., rainfall/smowmelt) event volumes.

![from etal (1975)](images/Reed1_small.png)

#### References

Reed, D.W., P. Johnson, J.M. Firth, 1975. A Non-Linear Rainfall-Runoff Model, Providing for Variable Lag Time. Journal of Hydrology 25: 295–305.