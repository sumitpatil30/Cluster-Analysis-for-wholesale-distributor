# Cluster-Analysis-for-wholesale-distributor
Performed a cluster analysis for clients of wholesale distributor and recommended actions to improve sales for each cluster

# Process
Performed EDA then used k-means clustering algorithm for clustering the retailers. Also used t-SNE to visualize all clusters in 2-D plane

# Output
Based on given sales data for Feb’17, 5 clusters (Cluster 'A' , 'B' , 'C' , 'D' , 'E') are made.Recommendation for each cluster is also provided

Cluster A : Non-buyers
- Out of 9938 retailers, 6449 retailers are not buying any of the 12 brand.
- Since the data given is of Feb 2017, these retailers might have been buyers of some brand in previous months.
- Recommendation : Analyse the purchase data of these retailers for past -months, then assign them in cluster B, C, D or E.

Cluster B : Speciality stores / Speciality retailers 
- The retailers in this cluster only buy 1 brand out of available 12 brands. 
- This means they specialize in their product offering. 
- For example - Let's say Brand1 is 'Voltas AC' and Brand2 is 'Raymond Suits'. 
- Then, a retailer belonging to cluster B who selling electronic goods will only buy Brand1 and not buy Brand2.  
- There is no scope of cross-selling of Brands in this cluster. 
- To increase sales, a viable option is to give bulk discount on Brands.
- Recommendation : Give bulk discount on Brands for retailers in this cluster.
