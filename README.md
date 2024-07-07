# README


# DSCI 554 Assignment 2: Bubble Cloud Visualization - Country Infographic

This project presents a bubble cloud visualization of the 2005 capital city populations for developed and underdeveloped countries. Two visualizations are provided: one created using Inkscape SVG Editor and the other using SVG code directly. The visualizations use different design choices to convey the same data

## Data
- SYB61_253_Population Growth Rates in Capital cities.csv
-- This dataset contains information about the population growth rates in capital cities.
- SYB65_230_202209_GDP_real rates of growth_2005.csv
-- This dataset includes data on real GDP growth rates in 2005.

## Design Choices

### Inkscape SVG Editor Visualization

- **Layout**: The Inkscape-generated visualization employs a circular layout, utilizing bubbles to represent each country's capital city. The size of each bubble is proportionate to the population of the city, with larger bubbles denoting higher population sizes.
- **Color**: The color scheme is thoughtfully selected to convey information about the economic development status of each country. Bubbles are shaded in varying tones of green, helping viewers quickly discern between developed and underdeveloped nations based on the real GDP growth rate.
- **Typography**: Within each bubble, you'll find well-centered labels that contain two crucial pieces of information: the population count and the name of the country. Font sizes are dynamically adjusted to ensure they fit comfortably within the confines of the bubbles while maintaining readability.
- **Spatial Encoding**:
The arrangement of bubbles is geographically intuitive, with countries from the same continent clustered together. This spatial organization closely resembles the real-world geographical positions of these nations. For additional clarity, a legend is provided below the visualization, clearly indicating which continent each bubble cluster represents.
- **Creation Process**:
Install Inkscape.
Create a New Document.
Add Circles for Bubbles.
Customize Circle Properties.
Add Labels.
Group Elements.
Export the visualization as an SVG file for web or further editing.

### SVG Code Visualization

- **Layout**: The SVG code-generated visualization takes a grid-like approach, where bubbles (circles) are strategically positioned. As with the Inkscape version, the size of these bubbles corresponds to the population of the capital city they represent.
- **Color Encoding**: Colors play a dual role in this visualization. They are used to distinguish between different continents, making it easy for viewers to identify the geographical regions. Additionally, a legend is thoughtfully included below the visualization to clarify the continent-color associations.
- **Typography**: Labels in this version are centered directly above each bubble, optimizing readability. Font sizes are adjusted as needed to ensure that the country names and population counts are clear and legible.
- **Creation Process**:
Translating the Inkscape Design into SVG Code
Create an HTML File
Embed the SVG
Adjust SVG Attributes
Style with CSS

## Conclusion:
Both visualizations are crafted to effectively convey information about capital cities, their populations, and the economic development status of the respective countries. While the Inkscape version emphasizes geographical clustering, the SVG code version adopts a more structured grid layout, each catering to different visual preferences and storytelling approaches.

## Integration

The HTML page integrates both visualizations using SVG. It ensures consistency in design elements, such as color and labeling, while presenting the same data in two distinct layouts.

## Technologies Used

- HTML: For structuring the web page.
- SVG: For creating the visualizations.
- Inkscape: For generating the first visualization.
- JavaScript: For dynamic data population in the SVG code visualization.
- CSS (style.css): For styling the HTML elements.
