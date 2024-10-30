# Long-Term Sea Surface Temperature and Indian Summer Monsoon Rainfall Dataset
This dataset consists of the Sea Surface Temperature (ERSSTv5; 2° x 2°) Anomalies and the June-July-August-September averaged annual rainfall over India (IMD; 1° x 1°) over 120 years starting from 1901 to 2020.
The SST data has been cleaned of the seasonal cycle and the trend at each grid point, thus isolating the inter-annual variability.

## Data Variables
1. Year: Calender Year
2. NP1_SST: Sea Surface Temperature Anomaly in 120°E - 140°E; 20°N - 35°N
3. NP2_SST: Sea Surface Temperature Anomaly in 155°E - 175°E; 30°N - 45°N
4. N34: Sea Surface Temperature Anomaly in Nino3.4 region 170°W - 120°W; 5°N - 5°S
5. EEIO: Sea Surface Temperature Anomaly in Eastern Equatorial Indian Ocean 80°E - 110°E; EQ - 10°S
6. Rainfall: Classification of the annual rainfall (JJAS averaged) over India (+1: Flood Year ; 0: Neutral Year ; -1: Drought Year)

## Data Processing
1. Sea Surface Temperature: The seasonal cycle of the Sea Surface Temperature was removed by subtracting the monthly climatology at each grid point. The linear trend of the SST at each grid was removed. The SST values consists of only inter-annual variability.
2. Rainfall: The All-India Rainfall June-July-August-September averaged annual rainfall was normalized. $R_i > 1 \sigma = 1$ ; $R_i <-1 \sigma =-1$ ; and $-1\sigma < R_i<1 \sigma=0$

## Data Format
The dataset provided is CSV file containing 120 rows and 5 cols, each row representing a year and each col representing the data variables.
