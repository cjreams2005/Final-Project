# Final-Project-CMPINF-0010
## Team Name: kc^2, Group 52
Measuring the best neighborhoods to go on a walk in based on number of water features, trees, and parks.

### Full Description 
We're looking to find the best neighborhood in Pittsburgh for going on relaxing walks together while having a good yap (fufilling conversations). In order to find the best neighborhood for taking a chill walk, we have decided on three metrics: water features, trees, and park features. The amount of trees relates to overall environment with nature as well as cleaner air quality for creating a refreshing outside environment that allows for fresh air during walks. Park features as well as water features allows for more fun, convienient, and recreational activities to stop by and possibly have fun with during walks.

## Metics and Overall Metric EXPLAINED
Number of Parks, Number of Water Features, Number of Trees

$$
\text{Overall Metric} = \frac{\text{Number of Parks Ranking (Neighborhood)} + \text{Number of Water Features Ranking (Neighborhood)} + \text{Number of Trees Ranking (Neighborhood)}}{3}
$$


The ranking of each individual metrix is defined as its "place" when sorted in descnding order based on the individual metric, i.e. the neighborhood with most about of trees would be rank 1, the second most would be rank 2, etc. So if a neighborhood was rank 1 in parks, rank 5 in water features, and rank 3 in trees, the overall metrix score would be $\frac{1 + 5 +3}{3} = 3$. 

So, the best neighborhood based on the overall metric is the one with with the smallest overall metric.
## Team Members and Datasets
### CJ Reamer (cjr167@pitt.edu) (Water Features)
A dataset for all the water features in each neighborhood in Pittsburgh.

### Carly Bowen (cab582@pitt.edu) (Trees)
https://data.wprdc.org/dataset/city-trees/resource/1515a93c-73e3-4425-9b35-1cd11b2196da
A dataset for all the trees and the number of trees in each neighborhood in Pittsburgh.

### Kenny Han (dih37@pit.edu) (Number of Parks)
https://data.wprdc.org/dataset/parks1
A dataset for the geographical data on where parks are.

https://data.wprdc.org/dataset/neighborhoods2
A dataset for the geographical data on where the neighborhoods are.

Combined the two to find the neighborhoods tha contains the most amount of parks.

### Note
Each of the datasets were downloaded from WPRDC as csv into the `data` folder and read in each of our notebooks to do our work.
The final and individual metric results were stored in the `final_metric` folder.

## Notebooks and Submission 
**Final Notebook:** group_52_final_notebook.ipynb

**Kenny Han Notebook:** parks.ipynb

**Carly Bowen Notebook:** trees.ipynb

**CJ Reamer:** water_features.ipynb



