# Soccer-Network-Analysis
Network Analysis of Soccer Data

Introduction

The goal of this research primarily focused on classifying soccer match outcomes through each game’s respective passing networks. Firstly however, what is a passing network. A passing network is a directed weighted graph where each node symbolizes a player, and each edge symbolizes a pass between each player with the weights for each edge being made up of total pass counts. In each network, the node location is defined by the average X and average Y coordinate. For example, if player one receives the ball once at (1,2) and a second time at (1,4) then his average location would be (1,3). These networks can differ significantly from game to game. For example, look at the network below from AFC Bournemouth vs. Tottenham Hotspur. In this game, Tottenham Hotspur won 5-1 and there are certain characteristics that the "winning" passing networks share. This includes things such as the outside defensive players having average X and Y coordinates that are close to the striker. In the Tottenham Hotspur network, Rose and Walker both have an average X coordinate that is only slightly less than Tottenham striker Harry Kane. In terms of the losing passing network, it also shares certain characteristics. These include most of the nodes on the left side of the pitch as well as one of the attacking players being disconnected from the rest of the network.

To classify these networks, I created two separate models. The initial model employs a K-Nearest-Neighbors model and incorporates centrality measures along with specific attributes as graph embeddings. The second model is also a K-Nearest-Neighbor model but utilizes a distance function based on the distances between players in each position and the corresponding passing weights.

![image](https://github.com/barrettb/Soccer-Network-Analysis/assets/89215081/ce9fcd45-f8d0-404f-912d-0d1062da08ea)

![image](https://github.com/barrettb/Soccer-Network-Analysis/assets/89215081/cd959072-d091-4cc2-bdbe-dd8b0a831de0)

![image](https://github.com/barrettb/Soccer-Network-Analysis/assets/89215081/55b13a79-610f-44f6-b0ce-c68d6b8475b0)

![image](https://github.com/barrettb/Soccer-Network-Analysis/assets/89215081/69fcd969-717b-47d9-95ec-879265274b87)

