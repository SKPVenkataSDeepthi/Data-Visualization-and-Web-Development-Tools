# Visualize Data with a Choropleth Map

This project is a **Choropleth Map** built using **D3.js**, **HTML**, **CSS**, and **JavaScript**. It fulfills the requirements of the **FreeCodeCamp Data Visualization Certification** and demonstrates proficiency in creating data-driven visualizations.

## Objective

Build an interactive choropleth map that is functionally similar to the example provided: [Choropleth Map Example](https://choropleth-map.freecodecamp.rocks). The map visualizes U.S. education data by county, with color coding to represent varying levels of educational attainment.

## User Stories

The project meets the following user stories:

1. **Title**: The map includes a title element with `id="title"`.
2. **Description**: The map includes a description element with `id="description"`.
3. **Counties**: The map includes counties with `class="county"`, each representing data from the dataset.
4. **Fill Colors**: The counties use at least 4 different fill colors to represent data ranges.
5. **County Data Attributes**: Each county has `data-fips` and `data-education` attributes containing their corresponding values.
6. **Data Points**: The map includes a county for each data point provided in the dataset.
7. **Matching Data**: The `data-fips` and `data-education` values match the sample data.
8. **Legend**: The map includes a legend with `id="legend"`.
9. **Legend Colors**: The legend uses at least 4 different fill colors to represent data ranges.
10. **Tooltip**: Mousing over an area displays a tooltip with `id="tooltip"`, showing additional information about the area.
11. **Tooltip Data**: The tooltip's `data-education` attribute matches the `data-education` value of the active area.

## Datasets Used

- **US Education Data**: [for_user_education.json](https://cdn.freecodecamp.org/testable-projects-fcc/data/choropleth_map/for_user_education.json)
- **US County Data**: [counties.json](https://cdn.freecodecamp.org/testable-projects-fcc/data/choropleth_map/counties.json)

## Solution Page

You can view my solution here: [Choropleth Map Solution](https://codepen.io/deepthi-Srikotapeetambaram/pen/ZYzJvWx)

### Instructions to Test

1. Open the solution link in your browser.
2. Click on **"Select Test Suite"** (top-left corner of the page).
3. Choose **"D3: Choropleth"** from the dropdown menu.
4. Click **"Run Tests"** to verify that all tests pass successfully.

### Viewing the Source Code

To view the source code, click the **"HTML", "CSS", or "JS"** tabs in the CodePen interface (top-right corner of the page).

## Tools and Technologies Used

- **D3.js**: For creating and manipulating the choropleth map.
- **HTML**: For structuring the web page.
- **CSS**: For styling the visualization and layout.
- **JavaScript**: For data fetching, processing, and interactivity.

## Features

- Interactive choropleth map with tooltip functionality.
- Dynamic legend and color scaling based on data values.
- Fully responsive and visually styled.

---

## Acknowledgments

This project is part of the **FreeCodeCamp Data Visualization Certification**. 

Happy Coding! 🎉
