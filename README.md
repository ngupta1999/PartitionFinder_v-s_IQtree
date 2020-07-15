# PartitionFinder v/s ModelFinder
  ## Results
  1. Different partitioning schemes were observed in both the analysis.
  2. The best partitioning scheme of IQtree merged two partitions together
         in order to have fewer independent variables.
         
  **IQtree's Modelfinder analysis best partioning scheme is shown below**
  
       DNAF, ef1a_1stpos_COI_1stpos = 1-649\3, 650-1415\3
       DNAF, ef1a_2ndpos_COI_2ndpos = 2-649\3, 651-1415\3
       DNAF, ef1a_3rdpos = 3-649\3
       DNAF, COI_3rdpos = 652-1415\3
       DNAF, 16S = 1416-1897

   It merged ef1a_1stpos, COI_1stpos and ef1a_2ndpos, COI_2ndpos into single partition.
   
   3. Partitionfinder analysis had less number of independent parameters than that in Modelfinder Analysis.
 
       
  **TREE from PartitionFinder**
      
![123456](https://user-images.githubusercontent.com/48491729/87574403-f21fb580-c6eb-11ea-96d3-f4fe684ef8bd.jpg)

  **TREE from Modelfinder**

![](https://user-images.githubusercontent.com/48491729/87333692-19934880-c55b-11ea-858e-6729a1f0d591.jpg)

  **TREE from Unpartitioned Model(GTR+F+R4 model was implemented)**

![](https://user-images.githubusercontent.com/48491729/87254761-8f87a900-c4a2-11ea-9f68-792918ef9cee.jpg)

  * The trees were constructed using FigTree software.
  * After the Partitionfinder analysis and IQtree analysis tree files were obtained for each of them in **Newick format**. 
  * According to the AICc values it was observed that the TREE obtained by performing **Partitionfinder** is closest to the reality with the
    **AICc value of 37169.4598237** (AICc for IQtree and Unpartitioned model are respectively  37199.6958 and 39233.2597)






   
