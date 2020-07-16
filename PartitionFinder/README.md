# DESCRIPTION
### 1. Commandline 
       python "<path to the PartitionFinder.phy file>" "<path to the folder containing alignment and configuration file>"
NOTE: Alignment file and the configuration file must be in the same folder
### 2. Configuration File 
       1. models = all
   (To consider all the 56 possible models.)
   
       2. schemes=all
   (Since, the dataset contains datablocks less than 12 so using "all" is computaionally feasible and will give more accurate results.)
   
       3.model_selection=aicc
   (Best model was selected on the basis of aicc value)   
### 3. Results
1. All 56 models were considered with +I, +G, +I+G, version of each. 
2. Total number of partitioning schemes were 877 abd the best scheme was chosen one with AICc value 37181.7739.
3. Total number of independent paramerters were 146.



     
