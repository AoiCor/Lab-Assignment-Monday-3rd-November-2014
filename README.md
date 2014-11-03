Lab-Assignment-Monday-3rd-November-2014
=======================================
IS30320 - Current Trends in Social Computing
--------------------------------------------

Aoife Corcoran 
------------
14200321
-----------

*Note: For this report I have used a modified version of the graph submitted on 10/10/14 for the lab assignment. The new version has been uploaded to blackboard.* 

Social Network Graph Report
----------------------------

This is a graph illustrating a subgroup of my personal Facebook network. This report will first outline the characteristics of the graph and how the information is illustrated and will then detail the process of producing the graph. 

Each of the nodes in the graph represents an individual Facebook user profile who all share a connection (in this case, that of a Facebook ‘friend’) with a common user (in this case myself). It is therefore considered to be an ego-centric network. The edges or connections can be seen between the nodes who are also Facebook ‘friends’ with each other, making it a 1.5 degree network. These are directed connections and, due to the nature of Facebook connections, they are always reciprocal. The graph only illustrates Facebook ‘friend’ connections between the individual nodes, although other connections may exist and it is therefore a uni-modal network. 
 
The graph is filtered to display only nodes with a degree rank of between 11 and 20. The filtered graph contains a total of 45 nodes and 100 edges. Unfiltered, a graph of the same social network contains 189 nodes and 1840 edges connecting them. The average connection degree of a node in this illustration is 2.222 whereas, unfiltered, the average degree is 9.735.  The nodes are sized based on their betweenness centrality, we can therefore visualise quite easily which nodes are the most influential within the social network. It is interesting to note that the most influential people in the network are not always those with the most connections, but are also those who have one or two important bridging connections. 

The graph shows three distinct clusters of nodes, which are coloured according to modularity class. The filtering of the graph means that we only see nodes with a modularity class of 2 or 3 (2 = yellow, 3 = green). These clusters demonstrate the communities of connectivity that exists within this social network. We can see that there are strong ties (connections supported by other mutual connections) within the two green communities but quite weak ties between them. The yellow cluster has very few strong ties, with most nodes being connected to only two or three others. Three of the nodes in the yellow cluster have only one weak connection to the network. Only three nodes are connected outside their community, forming bridging ties. As previously mentioned, many of these are the same nodes with a high betweenness centrality. The high level of clustering in this social network makes sense when we examine the individual user profiles. The people in the green cluster all went to the same secondary school, and the people in the yellow cluster have all lived in the same city in the past five years. There are very few links between them because geographical distance means there are very few common connections. 

In order to create this graph, information was gathered from Facebook using the NetVizz web app and was then manipulated using the open source visualisation programme Gephi. A modularity algorithm was applied to the data followed by a ‘Force Atlas’ layout in order to make the clustering more apparent. The nodes were then coloured based on their modularity class to make this clustering more visually obvious. Once the communities within the network were identified, the nodes were filtered based on their degree range in order to achieve the subset we see illustrated. The nodes were filtered to this narrow degree in order that the finished graph might achieve a degree of clarity known as ‘Netvizz Nirvana’. Once filtered to a suitable subset of the entire network, the nodes were resized (using the ranking toolbar) based on their betweenness centrality. The parameters were set to illustrate betweenness centrality ranging from 0.0 to 4.6 and with the sizing set to range from 10 - 25. This made it clear which nodes within the social network were the most influential. The specific parameters were chosen to make this information more visually striking and clear. Finally the ‘Force Atlas’ layout was applied again, this time with a high repulsion strength (300) so that the remaining nodes would form more coherent clusters while separating them out from one another to leave us with a less cluttered graph. The final graph clearly illustrates the communities, connections and people of influence that exist within this social network. 

