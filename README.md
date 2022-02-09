# COVID_VaccineClinics 
### Project Title 
Network Analysis of COVID-19 Vaccine Clinics for Demographic Accessibility

### Name(s) of individual or team members
Lucy Roberts & Mason Leavitt

### Short 1-2 sentence summary
We will be performing a network analysis of COVID vaccine clinic in order to assess accessibility to various demographics. 

### Problem statement, question(s) and/or objective(s)
In our analysis, we are hoping to explore the accessibility of COVID-19 vaccine sites to various demographics. In incorporating ACS/census data into our analysis, we can better understand how the availability of COVID clinics to underserved populations.

### Datasets you will use (with links, if available)
##### COVID-19 Vaccine clinic locations
https://hub.arcgis.com/datasets/c50a1a352e944a66aed98e61952051ef_0/explore?location=12.372907%2C-7.480419%2C1.55
##### ACS 2019 Community data
Accessed through cenpy
##### OSM Road network data
Accessed through osmx

### Tools/packages we will need
- Open Street Map
- Folium
- Numpy
- Geopandas
- Cenpy
- jupyter
- networkx
- matplotlib

### Planned methodology/approach/Site Selection
	We will be evaluating the network accessibility of COVID vaccine clinics in Detroit Michigan.  Our goal will be to create an isochrone network from points of vaccine clinics to analyze how many US census block groups are within an accessible walking or driving distance. We want to explore if there are disparities in accessibility along racial-ethnic lines, hence our decision to analyze accessibility in conjunction to US census data.

	We selected Detroit Michigan as a site for the analysis for a couple of reasons. One, Detroit doesn't have an effective mass transit system, meaning residents must largely rely on cars and walking as a mode of transportation, which OSM is effective for evaluating. Two, the city is racially segregated, and has struggled with racial inequality for decades. This analysis could illuminate how those disparities might be exacerbated by differential vaccine access, which is especially pertinent given racial disparities of deaths across the US. Additionally, we might evaluate how access correlates with medium income, car accessibility, and other metrics offered in the ACS.

### Expected outcomes
	We are not sure about the outcomes expected from this analysis. We envision producing maps, descriptive statistics, or perhaps a combination of the two. We suspect vaccine access will be better served towards white individuals, but that remains to be seen.
Any other relevant information, images/tables, references, etc.

### References
American Community Survey
US Census Bureau
GIS Corps

