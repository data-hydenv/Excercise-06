# Task 3
Create a view called *indices* on the hobos table. It should collect a number of indices for each HOBO and indexed by the id (not hobo_id!).
Calculate the following numbers: 

* mean of day temperatures 
* variance of day temperatures
* mean of night temperatures 
* variance of night temperatures
* 90% percentile of day temperatures
* 90% percentile of night temperatures

Create a map of all hobos, either using QGis or leaflet in RMarkdown. Show one index on each map and select the one map that illustrates spatial variablility of one of the indices. Discuss the decision on Github, before you accept the final pull request to submit the solution.

Use the *districts* table to join the *indices* to the city districs in Freiburg. Does this spatial aggregation change the overall picture? 
