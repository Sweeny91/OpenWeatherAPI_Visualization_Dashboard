# Web Visualization Dashboard 

## Background

In this repository I took what was learned about HTML and CSS to create a dashboard showing off an analysis that was completed in the Sweeny91/api_challenge repository.

![Images/landingResize.png](Instructions_Images/landingResize.png)

## Latitude - Latitude Analysis Dashboard with Attitude

A visualization dashboard website was created using visualizations that were earlier created using API calls obtaining weather data. Specifically, [weather data](Resources/cities.csv) was plotted.

### Website Requirements

The website consists of 7 pages total, including:
* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page. (preview images of each plot, and clicking an image takes the user to that visualization)
* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page for easy comparison.
  * Implements a Bootstrap grid for the visualizations.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
  * The data comes from exporting the `.csv` file as HTML, using the pandas library within a jupyter notebook for simplicities sake.

(For reference, see the ["Screenshots" section](#screenshots) below.)

In this website, at the top of every page there is a navigation menu that contains:
* The name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). The nav has a similar behavior to the screenshots ["Navigation Menu" section](#navigation-menu).


### Screenshots

This section contains screenshots of each page that was be built, at varying screen widths.

#### <a id="landing-page"></a>Landing page

Large screen:

![Landing page large screen](Instructions_Images/landingResize.png)

Small screen:

![Landing page small screen](Instructions_Images/landing-sm.png)
￼

#### <a id="comparisons-page"></a>Comparisons page

Large screen:

![comparison page large screen](Instructions_Images/comparison-lg.png)

Small screen:

![comparison page small screen](Instructions_Images/comparison-sm.png)

#### <a id="data-page"></a>Data page

Large screen:

![data page large screen](Instructions_Images/data-lg.png)


Small screen:

![data page small screen](Instructions_Images/data-sm.png)

#### <a id="visualization-pages"></a>Visualization pages

You'll build four of these, one for each visualization. Here's an example of one:

Large screen:

![visualize page large screen](Instructions_Images/visualize-lg.png)

Small screen:

![visualize page small screen](Instructions_Images/visualize-sm.png)

#### <a id="navigation-menu"></a>Navigation menu

Large screen:
![nav menu large screen](Instructions_Images/nav-lg.png)

Small screen:
![nav menu small screen](Instructions_Images/nav-sm.png)

### Copyright

Trilogy Education Services © 2019. All Rights Reserved.
