AeroAi Cluster – Understanding Airline Delays

## Airline Delay Analysis Using Data Mining (Clustering) Overview ##

AeroAi Cluster is a data mining project developed in R that analyzes U.S. airline flight delays during December 2019 and December 2020.
Using unsupervised learning (K-Means clustering), the project identifies patterns and major causes of airline delays to support airlines, airport authorities, and public-sector decision makers.

## Research Question ##
What were the principal factors that contributed to airline delays during December 2019 and 2020?

## Full Project Video ##
📁 https://drive.google.com/file/d/1oFlL3sBX4bMxxTLVR1IlSDKRilWz_x5K/view?usp=drivesdk

## Dataset ##
- Source: Bureau of Transportation Statistics
- File: airline_delay.csv
- Records: 3,351
- Period: December 2019 & December 2020
- Features: Flight arrivals, delay counts, delay times, cancellations, diversions
  
## Methodology ##
- Imported and cleaned the dataset using R
- Removed missing values (na.omit)
- Selected delay-related numerical variables
- Applied min–max normalization
- Computed Euclidean distance matrix
- Determined optimal clusters using the Elbow Method
- Applied K-Means clustering (K = 3)
- Visualized clusters using scatter plots and heatmaps
  
## Key Results ##
- Algorithm: K-Means Clustering
- Optimal Clusters: 3
- Identified Clusters
- Cluster 1 – High Delay Airlines
- Severe delays mainly due to late aircraft, carrier, and NAS delays
- Cluster 2 – Best On-Time Performance Airlines
- Minimal delays and efficient operations
- Cluster 3 – Moderate Delay Airlines
- Average delays influenced by weather and NAS congestion
  
## Impact ##
- Improves airline performance evaluation
- Supports aviation policy and infrastructure planning
- Enhances passenger travel reliability
- Encourages efficient and sustainable air transport
  
## Conclusion ##

The study demonstrates the effectiveness of data mining and clustering techniques in identifying airline delay patterns.
The K-Means model successfully segmented airlines based on delay behavior, providing actionable insights for airlines and policymakers to reduce delays and improve operational efficiency.
