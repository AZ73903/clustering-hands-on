# clustering-hands-on
machine learning week 7 homework - written components are below


It is a jupyter notebook that can be run in jupyter or collab. 



Part B 3.- The scatter plot shows pretty darn clear that the setosa clusters together apart from the other two, which overlap some. The overlap is also visiblein the confusion matrix. In order to better visualize how k affects the results I ran both 3 and 5. 3 was better and 5 caused the clusters to split some where it wasn’t ideal. 

Part C 2.- 
Some data points where labeled as noise, -1, shown in the scatter plat as x’s. The clusters are not as clearly defined in dbscan. It doesn’t seem as useful here as K-Means was. 

K-means is strong because it is easy to understand and efficient particularly with larger data sets. Weakness is you must specify K in advance, necessitates the elbow method which helps choose the best K value.  

DBSCAN is strong because you do not need to specify a number of clusters in advance. It isolates noise effectively, which I would guess could be good or bad depending on the data set you are working with. Works better with clusters that are more randomly shaped. It struggles when there are differences in density, is harder on compute/ not as effective with high dimensionality large datasets. 


Part D

The real world example that seems pretty common is any segmenting or clustering customers together by any number of data points they share. That could be spending habits, demographics, preferences, etc. One idea I am actually working on is a tool to do this with employees in the context of potentially being impacted by AI in their current role. It is essentially a tool that clusters them by current skills and risk of displacement such that relevant support could be given in advance of the impact. A fair opportunity for everyone to improve and become the worker needed in the AI driven workplace. It is expressly never for the purpose of identifying who should be displaced. Of course, the ethical concerns are obvious and magnified whenever we speak about people. How can you do this short of surveillance in a way where you can assure it isn’t used to harm employees? I have ideas, but that repo is private, for now.
