# Delivery Store Optimization

Problem Statement :  A textile company in New York state, USA, must decrease expenses by minimizing delivery costs. One way to do that is to relocate warehouses closer to their distributors. The company employs 118 distributors across the state of New York. Demonstrate how an operations manager could segment distributors into five clustered geographies using the KMeans function and then identify five optimal warehouse locations central to those clusters The objective is to discover mapping coordinates that can be used to identify five central warehouse locations.

Note : In the solution I have made use of Silhouette method to find the optimal number of clusters instead of taking five clusters.
The problem statement was taken from [Qlik blog](https://help.qlik.com/en-US/cloud-services/Subsystems/Hub/Content/Sense_Hub/ChartFunctions/RankingFunctions/KmeansCentroidExample.htm)


Below is the results of potential warehouses loaction coordinates.

![image](https://user-images.githubusercontent.com/53835307/145912118-be2c07ce-5fc5-4d99-bee3-8e314c347606.png)
![image](https://user-images.githubusercontent.com/53835307/145912139-a50862d6-d769-4ded-be74-ff739e2c5ed7.png)
