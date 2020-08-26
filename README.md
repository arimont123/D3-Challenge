# D3 Homework - Data Journalism and D3

### Core Assignment: D3 Dabbler 
Created a scatter plot between`Healthcare vs. Poverty`.

Used D3 techniques to create a scatter plot that represents each state with circle elements. Pulled in the data from `data.csv` by using the `d3.csv` function.

* State abbreviations are included in the circles.
* Situated axes and labels to the left and bottom of the chart.
*Used `python -m http.server` to run the visualization. The page is hosted at `localhost:8000` in your web browser.

### Bonus: Impress the Boss 

#### 1. More Data, More Dynamics

You're going to include more demographics and more risk factors. Place additional labels in your scatter plot and give them click events so that your users can decide which data to display. Animate the transitions for your circles' locations as well as the range of your axes. Do this for two risk factors for each axis. Or, for an extreme challenge, create three for each axis.

* Hint: Try binding all of the CSV data to your circles. This will let you easily determine their x or y values when you click the labels.

#### 2. Incorporate d3-tip

Added tooltips to the circles which display each tooltip with the data that the user has selected. Used the `d3-tip.js` plugin developed by [Justin Palmer](https://github.com/Caged).

