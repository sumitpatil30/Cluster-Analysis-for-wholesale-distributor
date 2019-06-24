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

Cluster C : Retailers buying complementary goods
- The retailers in this cluster buy 2 brand out of available 12 brands.
- This means these retailers are buying complementary goods.
- For example - Let's say Brand4 is 'Tea' and Brand5 is 'Britannia Biscuits'.Then, a retailer belonging to cluster C will buy both these   Brands as comsumption of tea and biscuits generally goes hand-in-hand.
- To increase sales in this cluster , a viable option is to bundle Brands together and give discounts on bundeled Brands rather than on a single Brand.
- Recommendation : Bundle together brands and give discounts for entire bundle. 

Cluster D : Supermarket retailers
- The retailers in this cluster buy all combinations of brands but the number of such retailers is very less.
- This means these retailers are supermarkets.
- To increase sales in this cluster , a viable option is to give bulk discounts. 
- Also keep them informed about any new brands that might be available for sale in near future.
- Recommendation : Give bulk discount on Brands for retailers in this cluster.

Cluster E : General Store / Kirana Shops
- Each retailers in this cluster buy either 3 or 4 brands together.
- This means these retailers are general purpose shops ,i.e., kirana shops.
- For an established kirana shop, storing more quantity of particular Brand is always a challenge. 
- But selling them different Brands will be more efficient. Even selling them more than 4 Brands can be taken up as a challenge.
- Recommendation : Push for selling more then 4 brands.

