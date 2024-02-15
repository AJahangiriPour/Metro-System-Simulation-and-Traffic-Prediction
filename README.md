# Metro System Traffic Simulation

This Python code simulates the daily traffic in a metro system represented as a directed graph. The graph represents metro lines and stations, and the simulation generates data on passenger arrivals, departures, and line traffic for each station over multiple days.

## Dependencies
- NumPy
- Pandas
- NetworkX
- Matplotlib
- Scikit-learn

## Code Overview

1. **Graph Construction:**
   - Creates a directed graph representing metro lines and stations.
   - Nodes represent stations, and edges represent metro lines with distinct colors.

2. **Station Positions:**
   - Sets positions for nodes in the graph for visualization purposes.

3. **Station Rates:**
   - Assigns random rates for passenger arrivals and departures for each station.

4. **Simulation:**
   - Simulates daily traffic for each station, considering passenger arrivals, departures, and line traffic.

5. **Dataframe Merging:**
   - Merges simulation results for each day into a single dataframe.

6. **Visualization:**
   - Plots input, output, and line_after values over time for selected stations on the first day.

7. **One-Hot Encoding:**
   - Converts station names into one-hot encoded columns.

8. **Linear Regression Models:**
   - Fits linear regression models to predict passenger arrivals (in) and departures (out) for a specific station and time.

9. **AdaBoost Regression Model:**
   - Fits an AdaBoost regression model to predict the line_after values, representing the traffic on metro lines.

10. **System Traffic Analysis:**
    - Analyzes the average in and out rates for each station.

## Usage
1. Install the required dependencies using `pip install numpy pandas networkx matplotlib scikit-learn`.
2. Copy and paste the code into a Python script or Jupyter notebook.
3. Run the script or notebook to simulate and analyze metro system traffic.

Feel free to modify the code and parameters to explore different scenarios or improve the simulation.
