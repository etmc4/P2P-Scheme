# P2P-Scheme-Input-Data

## Below is a brief description of the data used in the P2P energy trading market

### 33_bus_data_1.csv: Contains the consumption data for 32 lots over the period of one day at every half an hour (32 by 48)
### solar_one_row_1.csv: Contains the solar generation data used for users who own PV solar panels, we assume that generation is the same for all 16 users the values are scaled by 150 to match the consumption data used.
### radial_33_bus_PTDF_origin.csv: Contains the PTDF matrix for the 33-bus distribution system.
### Power_Flow_Limits.csv: Contains the real power limits for each branch in the 33-bus distribution system. It is also used to calculate the congestion rate.
