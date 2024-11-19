# Final Project: Installing More Streetlights to Reduce Crime

## 1. Outline

### High-Level Summary
This project explores how the installation of new streetlights affects crime rates in urban areas. Using data from multiple cities, I aim to assess whether enhanced lighting correlates with reduced nighttime crime. By analyzing crime patterns before and after streetlight installations, this study provides data-driven insights for urban planning and public safety initiatives, and calls for action at the end.

### Project Structure
The project follows a clear narrative structure to guide the analysis:

1. **Introduction: Setting the Scene**
   - Discuss the importance of street lighting for urban safety and the motivation for this project.
   - Present the central research question: *Does the installation of streetlights reduce nighttime crime?*

2. **Methodology**
   - Outline data sources, including crime records, streetlight installation data, and demographic information.
   - Explain the analytical approaches, including before-and-after comparisons, buffer zone analysis, and nighttime crime rate evaluation.

3. **Analysis**
   - Present visualizations such as heatmaps, line charts, and buffer zone maps to highlight key findings.
   - Compare treated areas (with new streetlights) to control areas (without streetlights) to evaluate the effectiveness of the intervention.

4. **Findings and Discussion**
   - Summarize the key takeaways from the analysis.
   - Discuss potential limitations, such as demographic or socioeconomic confounding factors.

5. **Conclusion and Policy Recommendations**
   - Provide actionable recommendations for city planners and policymakers.
   - Suggest future research directions for improving urban safety through infrastructure upgrades.

---

## 2. Sketches

### Initial Sketches for Visualizations
1. **Heatmap of Nighttime Crimes:**
   - Visualizing crime density in areas where there are more streetlights versus where there are fewer.
   - Key elements: Intensity of crime hotspots, time filters for before/after comparison.
   - 

2. **Line Chart:**
   - Showing trends in nighttime crime rates before and after streetlight installation.
   - Key elements: Vertical marker for installation date, separated by city or neighborhood.

3. **Buffer Zone Map:**
   - Spatial analysis of crime incidents within a 100-meter radius of new streetlights.
   - Key elements: Buffer zones, crime density comparisons (before vs. after).

4. **Choropleth Map:**
   - Overlaying demographic data with crime rates for additional context.
   - Key elements: Population density, socioeconomic factors.

These sketches will help shape the story and visually support the findings.

---

## 3. Data

### Data Sources
- **Crime Data:**
  - **Source:** City police department datasets or open data portals.
  - **Examples:**
    - [NYPD Crime Data](https://data.cityofnewyork.us/)
    - [Chicago Crime Data](https://data.cityofchicago.org/)
  - **Description:** Includes records of crime incidents with fields for type, date, time, and geographic coordinates.
  - **Usage:** Analyze crime patterns before and after streetlight installations.

- **Streetlight Data:**
  - **Source:** City public works or infrastructure departments.
  - **Examples:**
    - [Boston Streetlight Locations](https://data.boston.gov/dataset/streetlight-locations)
    - [Los Angeles Streetlight Data](https://data.lacity.org/)
  - **Description:** Includes information on streetlight locations and installation dates.
  - **Usage:** Identify areas with new streetlights and measure crime rate changes.

- **Demographic Data:**
  - **Source:** U.S. Census Bureau (American Community Survey) or equivalent sources.
  - **Link:** [American Community Survey Data](https://data.census.gov/)
  - **Description:** Provides population density, income levels, and other socioeconomic information.
  - **Usage:** Control for confounding factors like population size and economic activity.

- **Geospatial Data:**
  - **Source:** OpenStreetMap or city GIS portals.
  - **Examples:**
    - [OpenStreetMap](https://www.openstreetmap.org/)
    - [Boston GIS Data](https://data.boston.gov/group/facilities)
  - **Description:** Provides spatial data for neighborhood boundaries and streets.
  - **Usage:** Create maps and buffer zones for spatial analysis.

### Data Accessibility
All datasets are publicly available through official portals. Links to datasets and processed data will be uploaded to the project’s GitHub repository for transparency and reproducibility.

---

## 4. Method and Medium

### Methodology
1. **Data Preparation:**
   - Clean and preprocess crime and streetlight datasets.
   - Standardize date formats and align geographic coordinates.
   - Merge datasets by location and time for analysis.

2. **Analytical Approaches:**
   - **Before-and-After Comparison:** Evaluate changes in crime rates after streetlight installations.
   - **Buffer Zone Analysis:** Assess crime density within 100-meter zones around new streetlights.
   - **Nighttime Crime Analysis:** Focus on crimes occurring between 8 PM and 6 AM to isolate the impact of lighting.

3. **Control Analysis:**
   - Incorporate demographic data to account for confounding factors like population density and income levels.

### Tools
- **Data Cleaning and Preprocessing:** Python (Pandas, Matplotlib, Seaborn).
- **Visualization:** Tableau for heatmaps, line charts, and interactive dashboards.
- **Geospatial Analysis:** QGIS or ArcGIS for mapping and spatial joins.
- **Presentation:** GitHub Pages for project documentation and results sharing.

### Deliverables
- An interactive map and dashboards in Tableau.
- A Shorthand presentation summarizing findings, visualizations, and policy recommendations. It will feature the visuals created in Tableau.
- All materials hosted on this GitHub repository.

---

## 5. Deliverables and Next Steps

1. **GitHub Project Page:**
   - Create a new Markdown file (`final_project.md`) documenting progress.
   - Include navigation to sketches, datasets, and visualizations.

2. **Visualizations:**
   - Finalize sketches and create interactive Tableau visualizations.
   - Upload visualizations to the GitHub repository.

3. **Next Steps:**
   - Begin data analysis and refine visualizations based on early findings.
   - Prepare a narrative that ties the data to actionable insights for urban planners.

---

## 6. References

- Zahed, Hasti. "How Does Streetlighting Impact Night Crime?" [Study](https://newsletter.economics.utoronto.ca/wp-content/uploads/How-Does-Streetlighting-Impact-Night-Crime-1.pdf)
- [NYPD Crime Data](https://data.cityofnewyork.us/)
- [Chicago Crime Data](https://data.cityofchicago.org/)
- [Boston Streetlight Locations](https://data.boston.gov/dataset/streetlight-locations)
- [American Community Survey Data](https://data.census.gov/)
- [OpenStreetMap](https://www.openstreetmap.org/)
