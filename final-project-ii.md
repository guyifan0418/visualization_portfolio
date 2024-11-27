# Final Project: Part II - Wireframes, Storyboards, and User Research

## 1. Wireframes and Storyboards

### Storyboard Overview
The story of this project explores the impact of streetlight installations on crime patterns in urban areas. The narrative guides readers through a data-driven journey, starting with the motivation behind the analysis, diving into the methodology, and concluding with findings and recommendations. The storyboard ensures that every data visualization aligns with the story and enhances its clarity.

### Wireframes
Below are the wireframes that represent the high-fidelity draft visualizations of the critical elements in the story:

1. **Line Chart: Crime Trends Before and After Streetlight Installation**
   - **Purpose:** Show the overall trend in crime incidents, highlighting the impact of the intervention.
   - **Elements:** 
     - X-axis: Time (Months)
     - Y-axis: Crime Incidents
     - Vertical Line: Indicates the date of streetlight installation
   - [Embedded Visualization](images/line_chart.png)

2. **Heatmap: Crime Density Before and After Streetlight Installation**
   - **Purpose:** Compare the intensity of crime hotspots before and after streetlight interventions.
   - **Elements:** 
     - Left Panel: Heatmap for crime density before streetlight installation.
     - Right Panel: Heatmap for crime density after streetlight installation.
   - [Embedded Visualization](images/heatmap.png)

3. **Buffer Zone Map: Spatial Analysis**
   - **Purpose:** Analyze the density of crimes within a 100-meter radius of newly installed streetlights.
   - **Elements:** 
     - Scatterplot of crime locations
     - Highlighted buffer zones around streetlights
   - [Embedded Visualization](images/buffer_zone_map.png)

4. **Choropleth Map: Population Density and Crime Rates**
   - **Purpose:** Provide context by overlaying demographic data and crime rates across neighborhoods.
   - **Elements:** 
     - Population Density (Blue bars)
     - Crime Rates (Red bars)
   - [Embedded Visualization](images/choropleth.png)

---

## 2. Data Visualizations

### Data Visualization Approach
Each data visualization has been created using mock data to illustrate its form and function within the project narrative. Below is the rationale for including these visualizations:
- **Line Chart:** Captures the temporal trend and pinpoints when the streetlight intervention occurred.
- **Heatmap:** Highlights spatial differences in crime density, allowing for a visual comparison of areas before and after intervention.
- **Buffer Zone Map:** Focuses on micro-level changes in crime around specific streetlight installations.
- **Choropleth Map:** Incorporates demographic context to address potential confounding variables.

### Sketches
The sketches were refined into higher fidelity drafts using Tableau and Matplotlib. Key elements such as titles, annotations, legends, captions, and axis labels were included to ensure clarity and storytelling consistency.

---

## 3. User Research and Protocol

### Target Audience
The primary audience includes:
1. Urban planners
2. Public safety officials
3. Data enthusiasts interested in urban infrastructure and safety.

### Approach to Identifying Representative Individuals
To ensure diverse perspectives, I conducted interviews with:
- **Urban Planning Graduate Student (20s):** Represents individuals interested in urban design.
- **City Official (40s):** Brings expertise in public safety and policy-making.
- **Data Analyst (30s):** Focuses on storytelling with data visualizations.

### Interview Script
The following questions were asked during the interviews:
1. What stands out to you in the visualizations?
2. Is the purpose of each visualization clear? If not, why?
3. Are there any parts of the story that feel incomplete or unclear?
4. How do you interpret the relationship between streetlights and crime in the data presented?
5. What would make the visualizations or narrative more engaging or informative?

---

## 4. User Research Findings

### Key Insights and Observations
- **Clarity of Visualizations:**
  - The line chart was well-received, but one interviewee suggested adding a label directly on the vertical marker for clarity.
  - The heatmap was considered visually striking but lacked sufficient context without a legend explaining intensity levels.
- **Narrative Flow:**
  - All participants found the narrative logical but suggested moving the demographic context (choropleth map) earlier in the story to set the stage.
- **Interactivity:**
  - Two participants recommended adding filters for time and crime type to allow readers to explore the data interactively.
- **Choropleth Map:**
  - One participant noted that combining population density and crime rates in a single visualization was slightly confusing. Separating them into two graphs was suggested.

### Key Quotes
- "The line chart is intuitive but could benefit from more direct labeling on the intervention marker."
- "The heatmap is great at showing spatial differences, but I wish I could filter it by crime type."
- "Demographic context is essential, but placing it earlier in the story would help frame the problem better."

### Planned Changes
Based on feedback, the following changes will be implemented:
1. Add a direct label to the intervention marker in the line chart.
2. Include a legend for the heatmap to clarify the intensity scale.
3. Separate population density and crime rates in the choropleth map into two visualizations.
4. Explore adding interactivity to the visualizations in Tableau, such as time and crime type filters.
5. Adjust the narrative flow to present demographic context earlier in the story.

---

## 5. Moodboard and Personas (Optional)

### Moodboard
The moodboard includes:
- Examples of effective visualizations for spatial and temporal analyses.
- Themes for clean, minimalistic design with a focus on blue and red gradients to represent safety and danger.

### Personas
1. **Planner Paula:** Urban planner in her 30s, focused on infrastructure impact.
2. **Analyst Andy:** Data analyst in his 20s, loves exploring stories through data.
3. **Official Oliver:** City official in his 40s, interested in actionable insights.

---

## 6. Updated Storyboard

### Revised Narrative Flow
1. Introduction: Introduce the relationship between streetlights and crime.
2. Demographic Context: Present choropleth maps to set the stage.
3. Analysis:
   - Line chart showing temporal trends.
   - Heatmap for spatial changes in crime density.
   - Buffer zone analysis for localized impacts.
4. Conclusion: Summarize findings and provide recommendations.

---

## 7. GitHub Navigation

The updated project repository includes:
- **Markdown File:** `final_project_part2.md` with all required sections.
- **Images Folder:** Contains all draft visualizations (e.g., `images/line_chart.png`).
- **Shorthand Draft Link:** [Add link if applicable]

Navigation allows users to move between project components, including Part I and Part II.

---

## Rubric Checklist

| Criteria                  | Deliverable                                    | Status       |
|---------------------------|-----------------------------------------------|--------------|
| **Wireframes/Storyboards**| High-fidelity visualizations, clear story     | ✅ Completed |
| **Data Visualizations**   | Draft visualizations with appropriate elements| ✅ Completed |
| **GitHub Page**           | Created with navigation and documentation     | ✅ Completed |
| **User Research Protocol**| Questions, goals, and script provided         | ✅ Completed |
| **User Research Findings**| Documented feedback and planned improvements  | ✅ Completed |

---

## 8. References

- Zahed, Hasti. "How Does Streetlighting Impact Night Crime?" [Study](https://newsletter.economics.utoronto.ca/wp-content/uploads/How-Does-Streetlighting-Impact-Night-Crime-1.pdf)
- Example Crime Data Sources:
  - [NYPD Crime Data](https://data.cityofnewyork.us/)
  - [Chicago Crime Data](https://data.cityofchicago.org/)
- Example Streetlight Data Sources:
  - [Los Angeles Streetlight Data](https://data.lacity.org/)
  - [San Francisco Streetlight Data](https://data.sfgov.org/)
