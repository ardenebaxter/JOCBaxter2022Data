# IJOC_Baxter2022_Data
Data and results for "Heterogeneous Multi-Resource Allocation with Subset Demand Requests" in INFORMS Journal on Computing

Folders Scaled_Rewards_0TC, Unscaled_Rewards_0TC, Scaled_Rewards, and Unscaled_Rewards hold the data and results for computational experiments 
with problem instances that have scaled and unscaled rewards, where OTC denotes problem instances that were solved with zero travel costs.

Each folder has two types of files:
1.) XR_YDemands_ZResources_#.txt: This is a data file for problem instance # with X resource types, Y demands, and Z total resources. Within the text file, line "d" is the number of demands, line "r" is the number of resource types, line "k" is the number of resources of each type, line "total" is the total number of resources, line "s" is the service times, line "t" is the start times, line "p" is the rewards, line "num_sources" is the number of resource starting locations, line "resources_at_sources" is the number of resources at each starting location, lines "m" are the resource subset requests for demands, lines "f" and "c" denote the demands x demands travel and cost matrices, respectively, and lines "f_bar" and "c_bar" denote the resource starting locations x demands travel and cost matrices, respectively.
2.) XResourceTypes_Y.csv: Summary of the results for X resource types where Y = "IP" means instances were solved with integer variables and Y = "LP" means instances were solved with variables relaxed. Columns are as follows: number of resource types, number of demands, number of resources, instance number, objective value, demands met, run time (sec), number of ones in A matrix, number of demands met whose subset request = k for k = 1, ..., number of resource types, number of demands NOT met whose subset request = k for k = 1, ..., number of resource types

Folder Bicriteria has the problem instance files used to generate Figure 1 and Figure 2 in the online supplement.

Folder Alt_vs_IPM has the problem instance files and results used to generate Table 2 in the online supplement.
    
