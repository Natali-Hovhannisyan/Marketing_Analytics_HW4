# Marketing_Analytics_HW4
## Social Network Analysis for Targeted Marketing
### Overview
This hypothetical business utilizes social network analysis techniques to identify influential individuals and communities within a network.
By analyzing the connections and properties of a network, such as edge betweenness, density, degree centrality, and community structure, 
this example can help organizations optimize their marketing campaigns by identifying the most influential individuals or communities to target.

### Dependencies
To run the code, you need to have the following dependencies installed:

networkx
pandas
numpy
matplotlib
heapq
matplotlib.colors
infomap
You can install these dependencies using the pip package manager.
```bash
pip install networkx pandas numpy matplotlib infomap
```
### Usage (What has been done)
1. Prepare the Network Data:
Prepare the network data in the format of an edge list. Each row should contain two nodes representing a connection.

2. Load and Analyze the Network:

- Import the necessary libraries.
- Load the network data from a file.
- Create a directed graph and add the edges to it.
- Perform various network analysis tasks, including:
      - Identifying bridges in the network based on edge betweenness.
      - Calculating the graph density.
      - Finding nodes with the highest and lowest degrees.
      - Determining nodes with the highest in-degree and out-degree.
      - Computing centrality measures (closeness, betweenness, and eigenvector centrality).
      - Detecting communities using the Infomap algorithm.

3. Interpret the Results:

- Examine the identified bridges in the network.
- Analyze the graph density to understand the level of interconnectedness.
- Explore the nodes with the highest and lowest degrees.
- Identify nodes with the highest in-degree and out-degree.
- Investigate the nodes with the highest centrality measures.
- Evaluate the communities detected within the network.

4. Visualize the Results:

- Visualize the communities within the network using network layouts.
- Highlight the influencers or remove them from the communities to observe the impact.

5. Targeted Marketing:

- Utilize the insights gained from the analysis to design targeted marketing campaigns.
- Focus on influential individuals or communities to maximize the impact of the campaign.
- Consider removing influencers to observe changes in community dynamics.
