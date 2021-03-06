# Web Design - Web Visualization Dashboard (Latitude)

## Background

Data is more powerful when we share it with others! The goal of this project was to develop a website to present results from the Global Weather Data Analysis project. Since the completed project files were available in a GitHub repository, the necessary data and visualizations were imported directly from that location. HTML with Bootstrap CSS was used to generate, format, and link the individual webpages to form the completed website.

For this project we'll be creating a visualization dashboard website using visualizations we've created in a past project. Specifically, we'll be plotting [weather data](Resources/cities.csv).

In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Questions

1. Develop a webpage presenting a summary of the project and the four associated visualizations.
2. Develop four webpages each presenting an individual visualization along with its associated analysis.
3. Develop a webpage presenting a comparison of the four visualizations.
4. Develop a webpage presenting a table of the raw data used to create the four visualizations.

### Datasets
1. https://github.com/LolitaDias/Web-Design-Global-City-Latitude-Analysis/tree/master/Resources/assets/images
2. https://openweathermap.org/api
3. https://github.com/LolitaDias/Web-Design-Global-City-Latitude-Analysis/blob/master/Resources/cities.csv

### Tasks

#### Website Requirements

The website consists of pages, including:

1. A [landing page](#landing-page) contains:
  * An explanation of the project.
  * Links to each visualizations page.
2. Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
3. A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
4. A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component.
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called `to_html` that allows you to generate a HTML table from a pandas dataframe. See the documentation [here](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html)

The website at the top of every page, has a navigation menu that:

1. Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
2. Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
3. Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
4. Is responsive (using media queries). The nav must have similar behavior as the screenshots ["Navigation Menu" section](#navigation-menu) (notice the background color change).

### Result
Finally, the website has been deployed to GitHub pages: https://lolitadias.github.io/Web-Design-Global-City-Latitude-Analysis/

