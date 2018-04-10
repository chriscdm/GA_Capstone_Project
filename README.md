# GA_Capstone_Project
Chris Marker's Capstone for Data Science Immersive
Background
The Capstone Project for the Data Science Immersive Program is meant to give student's an opportunity to go into depth on a topic that is of interest to them using their newly acquired skills. For my project, I chose to look at the patterns created by the movement of introduced/invasive species from the native country to the invaded country. Using this data, I created an adjacency matrix using Pandas and Numpy from which I could graph the subsequent network using NetworkX. I used The Louvain Method for Community Detection implemented by way of the Community Package to partition the network and identify distinct communities of countries based on the dispersal of species.

Data
I used data fro three sources -- the Global Register of Introduced and Invasive Species, the CIA World Factbook, and Catalogue of Life. The data was in a far less useable form than would be ideal and currently requires further cleaning to improve the results of the project. Though I have all of the invaded locations, currently I only have a small percentage of the origin locations of the invaded species. The data is available, but not in a readily useable form.

Conclusion
I have thus far achieved a modularity score of 0.194. I suspect this score will improve with improved data, though due to the global nature of today's world it is possible that very strong communities do not exist based on the dispersion of introduced species.
