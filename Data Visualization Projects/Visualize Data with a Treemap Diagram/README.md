# Visualize Data with a Tree Map

This repository contains my solution to the **Tree Map Diagram Project**, part of the **FreeCodeCamp Data Visualization Certification**. The objective of this project is to build an interactive tree map visualization using **D3.js**, fulfilling specific user stories and passing all tests.

## Objective

Create a tree map diagram that is functionally similar to [this example](https://treemap-diagram.freecodecamp.rocks). The app is built using **HTML**, **CSS**, **JavaScript**, and the **D3.js** library. 

The visualization dynamically represents hierarchical data, with tiles sized according to their data values. The project adheres to the required user stories and test cases provided by FreeCodeCamp.

## Live Demo

You can view the solution on **CodePen**:  
[Tree Map Solution](https://codepen.io/deepthi-Srikotapeetambaram/pen/bNbrawg)

### How to Test
1. Click on **"Select Test Suite"** in the top-left corner of the CodePen interface.
2. Choose **D3: Tree Map** from the dropdown menu.
3. Click **"Run Tests"** to verify that all tests pass successfully.

## User Stories

1. **Title and Description**  
   - The tree map has a title with `id="title"`.  
   - The tree map has a description with `id="description"`.  

2. **Tree Map Tiles**  
   - The tree map contains `rect` elements with `class="tile"`.  
   - At least two different fill colors are used for the tiles.  
   - Each tile has `data-name`, `data-category`, and `data-value` attributes corresponding to its dataset properties.  
   - The area of each tile is proportional to its `data-value`.

3. **Legend**  
   - A legend is present with `id="legend"`.  
   - The legend contains `rect` elements with `class="legend-item"`.  
   - The legend uses at least two different fill colors.

4. **Tooltip**  
   - A tooltip with `id="tooltip"` displays information when hovering over a tile.  
   - The tooltip has a `data-value` attribute corresponding to the active tile's `data-value`.

## Dataset Options

You can use any of the following datasets for the project:  
- [Kickstarter Pledges](https://cdn.freecodecamp.org/testable-projects-fcc/data/tree_map/kickstarter-funding-data.json)  
- [Movie Sales](https://cdn.freecodecamp.org/testable-projects-fcc/data/tree_map/movie-data.json)  
- [Video Game Sales](https://cdn.freecodecamp.org/testable-projects-fcc/data/tree_map/video-game-sales-data.json)  

In my solution, I used one of the above datasets to demonstrate the functionality.

## Technologies Used

- **D3.js**: For creating the tree map and legend.
- **HTML, CSS, JavaScript**: For structuring and styling the project.
- **AJAX**: For fetching the dataset.

## How to View Source Code

To view the source code, click on the **"View"** button in the top-right corner of the CodePen page. You can explore the HTML, CSS, and JavaScript code used to build this project.

---
## Acknowledgments

This project is part of the **FreeCodeCamp Data Visualization Certification** curriculum. 

---

Happy coding! 🎉


