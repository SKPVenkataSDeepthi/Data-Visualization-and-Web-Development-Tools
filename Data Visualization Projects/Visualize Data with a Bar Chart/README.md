# Visualize Data with a Bar Chart

This project is a solution to the **Visualize Data with a Bar Chart** task from the FreeCodeCamp **Data Visualization Certification**. The goal was to build a bar chart that meets the specified user stories and passes all the required tests.

You can view the live solution here: [Bar Chart Solution](https://codepen.io/deepthi-Srikotapeetambaram/pen/NPKvwmr).

---

## Objective

Build an app that is functionally similar to this example: [FreeCodeCamp Bar Chart Example](https://bar-chart.freecodecamp.rocks).  
The chart visualizes U.S. GDP data from the dataset provided [here](https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/GDP-data.json).

---

## User Stories

The project fulfills the following user stories:

1. **Title**: The chart has a title with `id="title"`.
2. **X-Axis**: The chart includes an x-axis with a `g` element having `id="x-axis"`.
3. **Y-Axis**: The chart includes a y-axis with a `g` element having `id="y-axis"`.
4. **Tick Labels**: Both axes contain multiple tick labels, each with a `class="tick"`.
5. **Bars**: The chart has a `rect` element for each data point, with a `class="bar"`.
6. **Data Attributes**: Each `.bar` element has `data-date` and `data-gdp` attributes matching the dataset.
7. **Order Matching**: The order of `data-date` and `data-gdp` attributes matches the dataset order.
8. **Height Representation**: Each `.bar` element's height accurately represents the GDP value.
9. **X-Axis Alignment**: The `data-date` attribute and corresponding `.bar` align with the x-axis values.
10. **Y-Axis Alignment**: The `data-gdp` attribute and corresponding `.bar` align with the y-axis values.
11. **Tooltip**: A tooltip with `id="tooltip"` appears when hovering over a bar, displaying more information about the data.
12. **Tooltip Data Alignment**: The tooltip's `data-date` corresponds to the `data-date` of the active bar.

---

## Features

- **D3.js**: The chart is built using the D3.js library, leveraging its capabilities for SVG rendering and axis generation.
- **Dynamic Tooltip**: Displays GDP and date information when hovering over a bar.
- **Responsive Design**: The chart adjusts to different screen sizes for better usability.

---

## How to Test

1. Visit the solution page: [Bar Chart Solution](https://codepen.io/deepthi-Srikotapeetambaram/pen/NPKvwmr).
2. Click on **"Select Test Suite:"** in the top-left corner.
3. Choose **D3: Bar Chart** from the dropdown menu.
4. Click **"Run Tests"** to verify that all tests pass successfully.
5. To view the source code, click the **"HTML", "CSS", or "JS"** tabs in the top-right corner.

---

## Dataset

The dataset used for this project is a JSON file containing U.S. GDP data from 1947 to 2015. It is fetched from the following URL:  
[https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/GDP-data.json](https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/GDP-data.json).

---

## Tools and Technologies

- **D3.js**: For creating the SVG-based bar chart and axes.
- **HTML/CSS/JavaScript**: For structuring, styling, and scripting the application.

---

## Acknowledgments

This project is part of the **FreeCodeCamp Data Visualization Certification** curriculum. 

---

Happy coding! 🎉
