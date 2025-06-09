# Cryptocurrency Clustering (Module 19 Challenge)

This project uses K-Means clustering and PCA to group cryptocurrencies by movement patterns. PCA improves cluster clarity and reduces feature complexity.

## Overview

We analyze cryptocurrency trends using unsupervised learning, identify crypto clusters, and compare results with and without PCA.

## Technologies Used

- Python  
- Pandas, NumPy  
- Scikit-learn (K-Means, PCA)  
- hvPlot, Matplotlib  

## Process

1. **Preprocessing**
   - Load market data.
   - Scale features for equal weighting.
2. **Clustering on Raw Data**
   - Apply K-Means to 24h and 7d price changes.
   - Visualize clusters in 2D.
3. **PCA Optimization**
   - Reduce dimensions with PCA.
   - Choose optimal components for clustering.
4. **Clustering on PCA Data**
   - Run K-Means on PCA output.
   - Compare cluster shapes pre- and post-PCA.
5. **Visualization**
   - Use scatter plots to show cluster differences.
   - Analyze patterns by principal components.

## Results

- PCA produces clearer, more distinct clusters.
- Key patterns remain intact while reducing redundancy.
- Final clusters reveal stronger trend groupings.

## Next Steps

- Test more cluster counts.
- Add volume and volatility features.
- Integrate time-series for dynamic insights.

### Assistance
- DU Xpert AI Learning Assistant  
- ChatGPT
