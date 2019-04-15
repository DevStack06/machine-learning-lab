This are the task performed in the Kmeans programme file
    
    1.use the g.csv file as a dataset
    2. Upload the data into environment
    3. Observe the data 
    4. We’ll need to drop the Channel and Region variables.  
    These are two ID fields and are not useful in clustering. So drop it.
    5. Set some seed value
    6. Apply the k-mean on dataset, with k=5
    7. Observe the #number samples in each cluster
 1   2   3   4   5 
 23  10 104 223  80 

    8. Observe the center of cluster against each features, like
Fresh      Milk   Grocery   Frozen Detergents_Paper Delicassen
1 49296.087  4983.783  5590.304 8285.783         962.2609  2543.6957
2 21263.700 37443.300 46710.600 6287.200       21699.4000  8743.3000
3 21200.058  3886.423  5138.933 4119.856        1131.5192  1690.3365
4  6052.812  3266.314  4092.054 2459.682        1214.1300   990.6099
5  4738.762 11609.013 18198.775 1515.388        8003.7750  1603.8000

    9. Interpret the cluster results
    10. Measure homogeneity of each cluster (SSE)
    11. Measure total SSE
    12. Measure the heterogeneity of cluster 
    13. Elbow measure: run the algorithm 100 time for k=2 to 20. 
    14. Draw the plot and observe elbow point. 
