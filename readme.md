# Long-Term Sea Surface Temperature and Indian Summer Monsoon Rainfall Dataset
This dataset consists of the Sea Surface Temperature (ERSSTv5; 2° x 2°) Anomalies and the monthly rainfall over India (IMD; 1° x 1°) over 122 years starting from 1901 to 2022 for the months of June, July, August and September.
The SST data has been cleaned of the seasonal cycle and the trend at each grid point, thus isolating the inter-annual variability.

## Data Variables
1. Year: Calender Year
2. NP1_SST (t-n): Sea Surface Temperature Anomaly in 120°E - 140°E; 20°N - 35°N at nth monthly lag
3. NP2_SST (t-n): Sea Surface Temperature Anomaly in 155°E - 175°E; 30°N - 45°N at nth monthly lag
4. N34 (t-n): Sea Surface Temperature Anomaly in Nino3.4 region 170°W - 120°W; 5°N - 5°S at nth monthly lag
5. EEIO (t-n): Sea Surface Temperature Anomaly in Eastern Equatorial Indian Ocean 80°E - 110°E; EQ - 10°S at nth monthly lag
6. Rainfall (t-1): Total Rainfall of the previous month (mm) (Not Valid for month of June as Monsoon starts in the month of June)
7. Rainfall (t): Total Rainfal during the month (mm)

## Data Processing
1. Sea Surface Temperature: The seasonal cycle of the Sea Surface Temperature was removed by subtracting the monthly climatology at each grid point. The linear trend of the SST at each grid was removed. The SST values consists of only inter-annual variability.

