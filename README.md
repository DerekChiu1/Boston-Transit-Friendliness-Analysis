# Boston Neighborhood Transit Friendliness Analysis
## Project Description
This project analyzes the friendliness of transit options of sidewalks and bike paths across all 23 Boston neighborhoods, in which the transit friendliness is measured by a score calculated based on the density of sidewalks and bikepaths for each area. A website is built as the final product that includes interactive maps showing the distribution of sidewalks and bike paths, as well as the transit friendliness score for each neighborhood. The interactive nature of plots enable users to freely zoom in/out, hover, and click the graphs to gain insights. Static visualizations like scatter plots and bar charts are also included to show the density of sidewalks and bike paths, and the relationship between neighborhood areas and the friendliness score. The goal is to help users understand the distribution and frienliness of sidewalks and bikepaths in Boston, as well as to compare whether there's unequal resource or access to these transit facilities between urban and rural neighborhoods. 

## Website Images
![Website_img1](https://github.com/user-attachments/assets/4df23ef0-adb1-49e5-831c-c606bfa6614c)
![Website_img2](https://github.com/user-attachments/assets/aa791980-3c22-4a2e-a2f4-70e273814468)
![Website_img3](https://github.com/user-attachments/assets/852239e3-310f-4d09-9ea7-f5ee1204b6ac)
![Website_img4](https://github.com/user-attachments/assets/b6023b85-3288-4cb4-b36e-d68e4cbfc20a)
![Website_img5](https://github.com/user-attachments/assets/0c9c4d72-8012-4c20-9eea-c0287a331490)
![Website_img6](https://github.com/user-attachments/assets/051d4f4e-ba9d-4087-8d25-b3aefdbf5d4c)
![Website_img7](https://github.com/user-attachments/assets/24f84cee-0023-48b1-a925-419a8d403b08)

## How to Install and Run the Website
### Dependencies:
  - matplotlib >= 3.9.2
  - geopandas >= 1.0.1
  - altair >= 5.0.1
  - pandas >= 2.2.2
  - numpy >= 1.26.4
  - folium >= 0.19.5
  - scikit-learn >= 1.6.1
  - D3.js >= version 7

### Instructions:
  1. Make sure all libraries in the above dependency list are installed to your current working environment
  2. Download the Visualizations.iypng file and all data files from the data folder
  3. Run the Visualizations.iypng file to get four of the five plots, including 2 maps, 1 bar chart, and 1 lollipop chart. Then, download the charts into the Plots folder (html extension for interactive plots, png for static plots)
  4. Download and run the index.html, website.css, and website.js files, which should create the last plot and website itself. By running index.html on live server, the website will launch on the browser

### Troubleshooting:
  - If there's error reading the data files, make sure they're in the Data folder and their names aren't modified after downloaded
  - If there's error with the libraries used, make sure they're all properly installed to your current environment, and the version are the same or newer than the versions in the dependency list
  - If there's error running the website, make sure live server is properly installed and your internet connection is stable and reliable

## How to Use the Website
### Website Overview:
This website can be splitted into 3 major parts. The first part contains introduction, data sources, and methodology, which explains the project's topic, data used, and our approach. The second part contains 5 visualizations, including 2 maps, 1 bar chart, 1 lollipop chart, and 1 scatter plot. The third part contains summary, conclusion, and references, which summarized and highlighted the project's key takeaways and referenced the information used throughout the project. In the second part, the bar chart shows the density (km/km²) of sidewalks and bike paths of all Boston neighborhoods, sorted increasingly based on sidewalk's density. The first map is a Boston map showing the distribution of sidewalks and bike paths, denoted by blue and red lines respectively. The second map is a choropleth map showing the transit friendliness score of all Boston neighborhoods, where the magnitude of scores are denoted by the change of darkness of colors representing each neighborhood. The lollipop chart shows the transit friendliness score for all 23 neighborhoods, sorted decreasingly. Lastly, the scatter plot shows the relationship between the area of neighborhoods and their transit scores. Under the title for each graph, there's a short description of the graph to help readers understand it and highlight the takeaways.

### Visit the Dataset
If you want to visit the datasets used for this project, go to the Data Source section where you'll find two sources, which are Data.Boston.gov and Mass.gov. Under these two sources, name of the datasets obtained from them are shown. By clicking the hyperlniks of the dataset names, you'll be directed to the pages where you can download the data. On these pages, you can also see description of the sources and datasets to better understand them.

### Interactive Functionalities:



## Analysis You Can Do Using This Website
- Is there an unequal distribution of resource and access to sidewalks and bike paths for any particular neighborhoods?
- What's the relatinoship between the neighborhood areas and their transit friendliness scores?
- What's the neighborhood with the highest or lowest number of bike paths?
- What percentage of the Boston neighborhoods have the sidewalk density over 20 km/km² ?
- Does higher number/density of bike paths correspond to higher number/density of sidewalks?

## Contributors
1. Kuan-Chun Chiu (Myself) - beagledirk1@gmail.com
2. Emily Nguyen - nguyen.emily@northeastern.edu
3. Aadit Bhatia - bhatia.aad@northeastern.edu
