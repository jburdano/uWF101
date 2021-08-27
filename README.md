# uWF101  |  Discover your personal water footprint! - TechLabs project summer term 2021
## An analysis of water amount needed to grow food items in different countries and suggestions towards a water-sustainable consumption

### Tasks
0. How to clean data (e.g., exclude unrepresentative uWF values)? (Jörg)
1. Which food items use the most/least water? (Nagehan)
2. From which countries should food items (not) be imported to save most water? (Nagehan)
3. In which countries do food items generally need most water? (Miriam)
4. (How) Did the water footprint change over time (2000-2015)? (Jörg) 
5. How do results change for food items when using 'typical' portion sizes? (Miriam)
6. What are recommendable substitute food items in order to save water (in calculator)? (Fiona)
7. Which patterns of temporal change are observable (1960-2016)? (Jörg)
8. How can the water footprint be calculated for a list of food items (in calculator)? (Fiona)
9. Are there simple ways to estimate the water footprint of a product using ancillary data? (Jörg)

## Files
### 1. Our code:
0. stat_joerg_allcrops.ipynb
1. Task1b_Nagehan.ipynb
2. task1_2_Nagehan .ipynb
3. task3_5_uWF-rankings-portions_Joerg.ipynb
4. task4_joerg_heatmap.ipynb
5. task3_5_uWF-rankings-portions_Joerg.ipynb
6. task_6_8_Fiona.ipynb
7. task4_joerg_heatmap.ipynb
8. task_6_8_Fiona.ipynb
9. task9_joerg_hist.ipynb

### 2. The data
Data has been downloaded from www.watertofood.org

#### Explanations:
15crops = preselected group of products mostly from Europe, 
allcrops = whole dataset with more than 200 items
5perc = cleaned data excluding uWF values when harvest weights lie below the 5th percentile
15countries = preselected group of countries in/around Europe
weight = harvest weight in t, calculated from WF [m³] divided by uWF [m³/t]
2016 = data only for the year 2016
1960-2016 = data for period from 1960-2016

#### Files with general total water footprint (WF) in m³:
+ watertofood_WF_15crops_15countries_1960-2016.csv
+ watertofood_WF_15crops_15countries_2016.csv
+ watertofood_WF_allcrops_15countries_1960-2016.csv

#### Files with unit water footprint (uWF) in l/kg:
+ watertofood_uWF-weight_15crops_15countries_1960-2016_5perc.csv
+ watertofood_uWF-weight_allcrops_15countries_1960-2016_5perc.csv
+ watertofood_uWF_15crops_15countries_1960-2016.csv
+ watertofood_uWF_15crops_15countries_2016.csv
+ watertofood_uWF_allcrops_15countries_1960-2016.csv

