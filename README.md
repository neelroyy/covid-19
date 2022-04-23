# Covid-19 In The United States
Looking at Covid-19 throughout the pandemic, we looked into multiple data sets to see what the progression of the pandemic looked like, how it varied by regions, and looked for different factors that may have influenced how the pandemic impacted different regions. 

# Methods Used
Line Charts, Bar Graphs, Scatter Plots, linear regression, mapping 

# Technologies
Matplotlib, Pandas, geopandas packages 

# Contributors
Indranil Roy, Jenna Jorstad, Rhiana Schafer, Ying Sun 

# Data Sources
1. Main COVID-19 Dataset: imported to pandas directly from website https://query.data.world/s/vk5mf4hyssjgd5iqtolztihap6xjpi
2. Vaccination Rates Dataset: us_state_vaccinations.csv
3. COVID-19 Testing dataset: COVID-19_Diagnostic_Laboratory_Testing__PCR_Testing__Time_Series.csv 
4. US State Populations dataset: NST-EST2021-POP.csv
5. US County Populations dataset: uscensuspop2020.csv
6. Shape Data: USA_States_Generalized.shp
7. Mask Mandates datset: imported to pandas directly from website 'https://data.cdc.gov/api/views/62d6-pm5i/rows.csv?accessType=DOWNLOAD'
8. County Diversity dataset: diversity_index_counties.csv
9. 2020 Election results dataset: ElectionResults2020.csv
10. US Poverty Rates datset: PovertyEstimates.csv

# Code File Explanations
<u><b>Analysis 1 - Case Count and New Case Count.ipynb</u></b>
<ul><li>Datasets: Main COVID-19 Dataset</li>
<li>Graphs Produced: <ul>
        <li>Total People Positive Case Count Over Time (daily, by week)</li>
        <li>People Positive New Case Counts Over Time (daily, by week)</li></ul></ul>
        
<u><b>COVID Vaccinations.ipynb</u></b>
<ul><li>Datasets: Vaccination Rates Dataset</li>
<li>Graphs Produced:<ul>
        <li>COVID-19 Total Vaccination Rates in the US over time</li>            
        <li>COVID-19 Total People Vaccinated in the US over time</li>
        <li>COVID-19 Daily Vaccination Rates in the US over time</li></ul></ul>
        
<u><b>IR_1.ipynb - can be deleted?</u></b>

<u><b>IR_Covid_19_Final.ipynb</u></b>
<ul><li>Datasets: <ul>
        <li>Main COVID-19 Dataset</li>
        <li>COVID-19 Testing Dataset</li>
        <li>US State Populations Dataset</li>
        <li>Shape Data</li></ul>
<li>Graphs Produced: <ul>
        <li>Total COVID-19 cases and deaths in US over time</li>
        <li>Total COVID-19 cases and deaths in each state</li>
        <li>Total COVID-19 tests in US over time, and %test </li>
        <li>COVID-19 tests vs. COVID-19 cases</li>
        <li>US map with COVID-19 cases and deaths</li></ul></ul>
        
<u><b>jennafile.ipynb</u></b>
<ul><li>Datasets: <ul>
        <li>Main COVID-19 Dataset</li></ul>
<li>Graphs Produced: <ul>
        <li>Total People Death Count Over Time</li>
        <li>New People Death Counts Over Time</li></ul></ul>
       
<u><b>rhiana_file.ipynb</u></b>
<ul><li>Datasets: <ul>
        <li>Main COVID-19 Dataset</li>
        <li>US County Population Dataset</li>
        <li>Mask Mandates Dataset</li>
        <li>County Diversity Dataset</li>
        <li>2020 Election Results Dataset</li>
        <li>US Poverty Rates dataset</li></ul>             
<li>Graphs Produced: <ul>
        <li>COVID-19 Case/Death rates in each state as percentage of total population</li>
        <li>Political party afflitiation vs. COVID-19 outcomes by county</li>
        <li>Poverty rates vs. COVID-19 outcomes by county, & overall and split by party</li>
        <li>Racial Diversity vs. COVID-19 outcomes, overall and split by ethnicity</li>
        <li>COVID-19 outcomes over time, split by mask mandate status</li></ul></ul>           
              
states.py: Dictionary for translating state abbreviations into full names

# Results Summarized and Presented here:
https://docs.google.com/presentation/d/19lU2e8rQZbQVZUvdm0qKNV4nQXz5wrsFhnQ6YitGQPI/edit#slide=id.g1256fb98159_0_4


# Installation 
Code was tested using Python 3.8. The environment used pandas and matplotlib

