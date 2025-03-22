# Network-Analysis-of-Extra-State-Wars-1816-2006-
This project analyzed extra-state wars (1816–2006) using Social Network Analysis to explore how countries engaged in conflicts. It examined relationships, war duration, and intensity to reveal historical patterns of involvement, especially among colonial powers.
Network Analysis of Extra-State Wars (1816–2006)
Summary of the Project
This project aimed to analyze historical patterns of extra-state wars involving colonial
and imperial powers using Social Network Analysis (SNA). The goal was to explore
relationships between actors (countries) engaged in wars and understand patterns of
involvement, duration, and intensity of conflicts.
Dataset
• Extra-State War Data v4.0 (1816–2006)
• Public dataset focused on wars involving state and non-state actors.
Tools & Libraries Used
Language: R
Libraries: igraph, sna, ggplot2, dplyr, threejs, tidyverse
Main Methods and Steps
• Created network graph where nodes represent countries (Side A and Side B), and edges
represent wars.
• Constructed two key edge attributes:
- Total Deaths (sum of battle deaths and non-state deaths)
- Duration (based on start and end year of conflict; adjusted missing values using
historical context)
• Built an undirected multigraph, allowing multiple edges between countries involved in
multiple wars.
• Expected high centrality and connectivity for imperialist powers (e.g., UK, France,
Portugal) and recent major actors (e.g., USA, Iraq, Afghanistan).
• Used the network structure to visualize historical influence and identify the most
conflict-involved nations.
Key Findings
• European colonial powers were among the most connected nodes.
• Conflicts involving the US, Iraq, and Afghanistan emerged prominently in modern
periods.
• The network visually captured global power dynamics and colonial history through
graph structure and edge attributes like war intensity and duration.
