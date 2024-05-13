# Traveling-Salesman-Problem-Beam-Search
This project implements a solution of Traveling Salesman Problem using the Beam Search algorithm, specifically focusing on a variant that applies a Greedy approach to optimize the path finding.

## Introduction
The Traveling Salesman Problem (TSP) is a well-known problem in combinatorial optimization. It involves finding the shortest possible route that visits a set of cities and returns to the original city. This project implements a solution using the Beam Search algorithm, specifically focusing on a variant that applies a Greedy approach to optimize the path finding.

## Problem Statement
Given a list of cities and the distances between each pair, the goal is to determine the shortest possible loop that a salesman can travel to visit each city exactly once and return to the starting city. This problem is further complicated by the need to minimize travel distance in the context of rising fuel costs.

## Solution Approach
This project uses the Beam Search algorithm, a heuristic search method that expands only a limited number of nodes at each level of the decision tree. Our implementation employs a fixed beam width and uses the accumulated travel distance as the heuristic value to guide the search.

## Features
 - **Beam Search Implementation:** Utilizes a Greedy heuristic to efficiently determine potential paths.
 - **Configurable Beam Width:** Supports adjusting the beam width to explore its impact on the solution quality.
 - **Distance Matrix Input:** Accepts a pre-defined distance matrix and city indices for flexible problem setup.
 - **Visualization:** Includes a Matplotlib plot showing the relationship between beam width and travel distance, aiding in the selection of an optimal beam width.
 - **Performance Analysis:** Examines different beam widths to assess their efficiency and effectiveness in finding the shortest path.
 - 
## Usage
 - **Setup the Environment:** Ensure Python 3.11 and required packages (matplotlib for plotting) are installed.
 - **Prepare Input Data:** Format your distance matrix and city list as specified in the script comments.
 - **Configure Beam Width:** Set the beam width parameter in the script to experiment with different values.
 - **Run the Solver:** Execute the script to find the shortest path and generate the plot.
 - **Analyze Results:** Review the output paths and distances for various beam widths.
   
## Output Format
The solution script will output the shortest path and the total estimated distance for the configured beam value. For multiple beam values, the results will include paths and distances for each configuration.

## Observations
 - **Best Beam Value:** The best Beam Value in the range 2-1000 is 972. The corresponding Total Distance for this Beam Value is **7295 miles**.
 - **Total Distance vs. Beam Value:** The graph shows the relationship between the Beam Values (ranging from 2 to 1000) on the X-axis and the Total Distance (in miles) on the Y-axis. As the Beam Value increases, it explores more potential paths, leading to varying total distances.
 - **Decreasing Trend:** The plot exhibits a decreasing trend in total distance as the Beam Value increases. This suggests that a higher Beam Value generally leads to finding shorter routes for the traveling salesman problem (TSP).
 - **Best Beam Value:** The code identifies and annotates the best Beam Value on the plot, denoting it with a red arrow and text. In this specific case, the best Beam Value within the range of 2 to 1000 is reported as {best_beam_value}, and the corresponding Total Distance for this Beam Value is {best_total_distance} miles.

![download (21)](https://github.com/Maryam189/Traveling-Salesman-Problem-Beam-Search/assets/76420523/c0aef1dd-1adb-4e10-824f-db1f69bd1f57)

## Contributing
**Contributions are Welcome!** Please send me a pull request or open an issue to discuss your ideas. If there's anything else you'd like to know about it, let me know. Feel free to reach me out at [MaryamKhalid](Maryamkhalid590@gmail.com)

