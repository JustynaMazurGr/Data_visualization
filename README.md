# Data_visualization

TASK 1: Draw a line graph presenting the monthly temperatures in Warsaw and Miami. To accomplish this, follow these steps:

Prepare data for both cities.
Draw a line graph for each city.
Customize the appearance of each line graph to make them distinct.
Adjust the Y-axis range corresponding to temperature values to ensure no data is cut off.
Add a legend to the graph - try to find the appropriate command on your own.
Save the generated figure as a PNG file (optionally adjust the DPI value to improve graph readability).
***********************************************

TASK 2: The attached file contains the results of a set of algorithms solving the Hamiltonian Cycle problem in a graph. In this transportation task, the goal is to find the shortest (in terms of distance) path passing through all points. An example of such a problem could be route selection for buses departing from a depot. The task analyzes three different algorithms that iteratively (over 100 iterations) construct a solution.

Read the data for each algorithm and present the relationship between the number of iterations and the quality of the solution (length of the path).
Add elements such as title, axis labels, and legend to the graph.
Color the line graph for the best algorithm in green and highlight it with a bold line style.
Save the generated figure as a PNG file (optionally adjust the DPI value to improve graph readability).
*************************************************

TASK 3: A set of 2000 investment portfolios is described by return and risk. Perform the following steps:

Read the data available in the file and then plot a scatter plot based on the data.
Use text labels to mark the following areas on the graph: high risk and high return area, low risk and low return area, Sharpe's portfolio surroundings (we can indicate the area by dividing the return range in half and selecting the middle of that range as the reference point).
Mark 500 portfolios with the lowest return in green.
Mark 500 portfolios with the highest return in red.
Save the figure to a file.
*************************************************

TASK 4: The Abalone dataset from the UCI Machine Learning Repository is provided. The dataset contains information about a certain species of marine snail. The first attribute indicates the sex (M, F, or I - male, female, or infant), while the last attribute indicates the number of rings on the shell, which is related to age. Present the following information on two separate charts:

The number of individuals belonging to each category (M, F, and I).
The average number of rings for each category (M, F, and I).
Decide on the type of chart that best represents the above information. Use Python scripts or any other tool to prepare the data.
***********************************************

TASK 5: Using the Abalone dataset from the previous task, create a scatter plot (using a different color for each category: M, F, and I) based on the parameters: length and whole weight. Additionally, utilize the Rings parameter as an indication of the size of each object on the graph. Employ faceting to present the results on three different charts, emphasizing a different category on each chart.
*************************************************

TASK 6: The Zoo dataset from the UCI Machine Learning Repository is provided. The dataset contains information about selected animal features. Present the following information on six pie charts:

* The number of animals that have feathers.
* The number of animals that lay eggs.
* The number of animals that can fly.
* The number of animals that are predators.
* The number of animals that are venomous.
* The number of animals that have a tail.
*************************************************

TASK 7: In the optimization problem of selecting strategies for a set of players, three algorithms have been implemented. Each algorithm generated a total of 100 different solutions. The key aspect of the solution is the highest available probability of strategy selection (data from the file). Plot the results on a scatter plot. Apply the following methods to improve the readability of the graph:

Faceting.
Sampling (select a sample size of approximately 20-25% of the entire set).
Present the results on the graph using four different point sizes: smallest - if the probability of selection is less than 0.25, larger - for probabilities in the range (0.25, 0.5], large - for probabilities in the range (0.5, 0.75], largest - for probabilities above 0.75.
************************************************

TASK 8: Prepare and save to a file 3D plots of the following functions:

Alpine "2" function:
f(x, y) = cos(x) * x * (1 + cos(y)^2)

Schubert function:
f(x, y) = ((cos(2 * x + 1)) + (2 * cos(3 * x + 2)) + (3 * cos(4 * x + 3)) + (4 * cos(5 * x + 4)) + (5 * cos(6 * x + 5))) * ((cos(2 * y + 1)) + (2 * cos(3 * y + 2)) + (3 * cos(4 * y + 3)) + (4 * cos(5 * y + 4)) + (5 * cos(6 * y + 5)))

Rastrigin function:
f(x, y) = (x^2 - cos(18 * π * x)) + (y^2 - cos(18 * π * y))
