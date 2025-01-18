# Visualize Data with a Heat Map

This project is a **Heat Map Visualization** built using **D3.js**, **HTML**, **CSS**, and **JavaScript**. It fulfills the requirements of the FreeCodeCamp **Data Visualization Certification**. The app is functionally similar to the example provided by FreeCodeCamp and passes all the required tests.

## Objective

Create a heat map that visualizes global temperature data, with interactive features and proper alignment with the axes. The project meets the following user Stories:

### User Stories

1. The heat map has a title with `id="title"`.
2. The heat map has a description with `id="description"`.
3. The heat map includes an x-axis with `id="x-axis"`.
4. The heat map includes a y-axis with `id="y-axis"`.
5. The heat map contains `rect` elements with `class="cell"` representing the data.
6. At least 4 different fill colors are used for the cells.
7. Each cell has the attributes `data-month`, `data-year`, and `data-temp`.
8. The `data-month` and `data-year` values of each cell are within the dataset range.
9. Cells align with their corresponding month on the y-axis.
10. Cells align with their corresponding year on the x-axis.
11. The y-axis includes multiple tick labels with full month names.
12. The x-axis includes multiple tick labels with years between 1754 and 2015.
13. The heat map includes a legend with `id="legend"`.
14. The legend contains `rect` elements.
15. The legend uses at least 4 different fill colors for its `rect` elements.
16. A tooltip with `id="tooltip"` appears on mouseover, displaying information about the hovered area.
17. The tooltip includes a `data-year` property corresponding to the `data-year` of the active area.

### Dataset

The dataset used for this project can be found here:  
[Global Temperature Dataset](https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/global-temperature.json)

---

## Solution

You can view my solution live and test its functionality here:  
👉 [Solution Page on CodePen](https://codepen.io/deepthi-Srikotapeetambaram/pen/YPKxYzo)

### How to Test

1. Open the solution link.
2. In the CodePen interface, click on **Select Test Suite** (top left).
3. Choose **D3: Heat Map** from the dropdown.
4. Click on **Run Tests** to verify that all the tests pass successfully.

### Viewing the Source Code

To view the source code, click on the **"HTML", "CSS", or "JS"** tabs in the CodePen editor.

---

## Tools and Technologies

- **D3.js**: For creating and rendering the heat map visualization.
- **HTML**: For structuring the content.
- **CSS**: For styling the heat map and legend.
- **JavaScript**: For adding interactivity and handling data.

---

## Acknowledgments

This project is part of the **FreeCodeCamp Data Visualization Certification**. 

Happy Coding! 🎉
