# PartitionFinder v/s ModelFinder
  ## Results
  1. Different partitioning schemes were observed in both the analysis.
  2. The best partitioning scheme of IQtree had merged two genes together
         in order to have fewer independent variables.
         
  **IQtree's Modelfinder analysis best partioning scheme is shown below**
  
       DNAF, ef1a_1stpos_COI_1stpos = 1-649\3, 650-1415\3
       DNAF, ef1a_2ndpos_COI_2ndpos = 2-649\3, 651-1415\3
       DNAF, ef1a_3rdpos = 3-649\3
       DNAF, COI_3rdpos = 652-1415\3
       DNAF, 16S = 1416-1897
       DNAF, mitochondrial_genome = 650-1897
       DNAF, nuclear_genome = 1-649
   It merged ef1a_1stpos, COI_1stpos and ef1a_2ndpos, COI_2ndpos into single gene.
   
   3. Partitionfinder analysis had less number of independent parameters than that in Modelfinder Analysis.
 
       
  **TREE from PartitionFinder**
      
![](https://user-images.githubusercontent.com/48491729/87254644-9104a180-c4a1-11ea-9b41-b163f94efe53.jpg)

  **TREE from Modelfinder**

![](https://user-images.githubusercontent.com/48491729/87254723-315ac600-c4a2-11ea-8283-1841c9a9dc49.jpg)

  **TREE from Unpartitioned Model(GTR+F+R4 model was implemented)**

![](https://user-images.githubusercontent.com/48491729/87254761-8f87a900-c4a2-11ea-9f68-792918ef9cee.jpg)

  The trees were constructed using FigTree software 
  According to the AICc values it was observed that the TREE obtained by performing Modelfinder is close to the reality with the
  AICc value of 75851.9964 (AICc for PartitionFinder's tree and Unpartitioned tree are respectively 37169.4598237 and 39233.2597)






   
