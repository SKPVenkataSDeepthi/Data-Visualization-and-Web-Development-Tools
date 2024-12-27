# Visualize Data with a Scatterplot Graph

This repository contains my solution to the **Scatterplot Graph Project**, part of the **FreeCodeCamp Data Visualization Certification**. The project involves building a scatterplot graph using **D3.js**, **HTML**, **CSS**, and **JavaScript**, fulfilling the required user stories and passing all associated tests.

## Project Overview

### Objective
Build an app that is functionally similar to this: [Scatterplot Graph Example](https://scatterplot-graph.freecodecamp.rocks).

### Solution
You can view my solution here: [CodePen Solution](https://codepen.io/deepthi-Srikotapeetambaram/pen/wBwqpvW).

- **Instructions**:  
  1. Open the solution link.  
  2. Click on "Select Test Suite" in the top-left corner.  
  3. Choose **D3: Scatter Plot**.  
  4. Click "Run Tests" to verify all tests pass successfully.  
  5. To view the source code, click the "HTML", "CSS", or "JS" tabs in the top-right corner of the CodePen editor.

## User Stories

The following user stories are implemented and verified:

1. **Title**: A `<title>` element with `id="title"` is present.
2. **X-Axis**: An x-axis with `id="x-axis"` is present.
3. **Y-Axis**: A y-axis with `id="y-axis"` is present.
4. **Dots**: Data points are represented as dots with the class `dot`.
5. **Data Attributes**: Each dot has `data-xvalue` and `data-yvalue` attributes reflecting its x and y values.
6. **Data Format**: `data-xvalue` uses integers or Date objects; `data-yvalue` uses Date objects for minutes.
7. **Alignment**: Dots align with the corresponding x-axis values.
8. **Alignment**: Dots align with the corresponding y-axis values.
9. **Y-Axis Labels**: Tick labels on the y-axis are in `%M:%S` format.
10. **X-Axis Labels**: Tick labels on the x-axis show the year.
11. **X-Axis Range**: X-axis labels are within the range of the actual data.
12. **Y-Axis Range**: Y-axis labels are within the range of the actual data.
13. **Legend**: A legend with `id="legend"` contains descriptive text.
14. **Tooltip**: A tooltip with `id="tooltip"` appears on mouse hover, displaying detailed information.
15. **Tooltip Data**: Tooltip has a `data-year` property matching the `data-xvalue` of the hovered area.

## Dataset
The project uses the following dataset:  
[FreeCodeCamp Cyclist Data](https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/cyclist-data.json)

## Technologies Used
- **D3.js**: For creating the scatterplot graph and axes.
- **HTML**: For structuring the project.
- **CSS**: For styling and visual enhancements.
- **JavaScript**: For logic and interaction handling.

## Acknowledgments
This project is part of the FreeCodeCamp curriculum.

Happy coding! 🎉
