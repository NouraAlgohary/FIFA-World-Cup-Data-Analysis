# FIFA-World-Cup-Data-Analysis

## Power BI Dashboard
You can view our interactive Power BI Report [here](https://app.powerbi.com/groups/me/reports/41614564-3ab7-4418-998e-ae25f0e83747/ReportSection?experience=power-bi). 

![Capture](https://github.com/NouraAlgohary/FIFA-World-Cup-Data-Analysis/assets/103903785/b998f44b-43f1-4a99-bb63-ebfb0552d672)


## Project Overview:
This project involves extracting, profiling, and analyzing FIFA World Cup data from the Wikipedia website. The primary focus is on creating a comprehensive report that includes key information such as the year, host country, champion, runner-up, final score, and the number of participating teams. The project aims to provide insightful visualizations for better understanding and interpretation of the data.

## Project Steps:
### 1. Data Extraction:

Extract data from the relevant tables on the Wikipedia page: [FIFA World Cup Wikipedia](https://en.wikipedia.org/wiki/FIFA_World_Cup) using Power BI import mode.

![image](https://github.com/NouraAlgohary/FIFA-World-Cup-Data-Analysis/assets/103903785/22a6e5f8-eb84-40c4-b6b1-614e1a57cfb4)


### 2. Data Profiling:
#### Data Types and Formats:
- Ed. (Edition):</br>
Data Type: Numeric</br>
Description: Represents the edition or number of the FIFA World Cup. It indicates the sequential order of each tournament.</br>

- Year:</br>
Data Type: Numeric</br>
Description: Indicates the calendar year in which the FIFA World Cup tournament took place.</br>

- Host:</br>
Data Type: Categorical</br>
Description: Specifies the country that hosted the FIFA World Cup for a particular edition.</br>

- Final, Third-place play-off, Champion, Runner-up, Third, Fourth:</br>
Data Type: Categorical</br>
Description: These columns provide information about the teams involved in different stages of the tournament:</br>
"Final" indicates the teams that reached the final match.</br>
"Third-place play-off" indicates the teams that competed for the third-place position.</br>
"Champion" indicates the team that won the championship.</br>
"Runner-up" indicates the team that finished as the runner-up.</br>
"Third" indicates the team that finished in third place.</br>
"Fourth" indicates the team that finished in fourth place.</br>

- No. of teams:</br>
Data Type: Numeric</br>
Description: Represents the total number of teams that participated in a specific edition of the FIFA World Cup.</br>

#### Statistical Summary:
Number of editions of the FIFA World Cup

![image](https://github.com/NouraAlgohary/FIFA-World-Cup-Data-Analysis/assets/103903785/d3fb47a6-65c8-40c2-b182-48b2d224c981)

Distribution of the World Cup years

![image](https://github.com/NouraAlgohary/FIFA-World-Cup-Data-Analysis/assets/103903785/93fb98db-d669-4590-a34b-2a43ae82f16f)

Frequency of hosting by countries

![image](https://github.com/NouraAlgohary/FIFA-World-Cup-Data-Analysis/assets/103903785/1bb7eb8d-5260-4075-810b-fd9074c00623)

Frequency of teams winning the championship

![image](https://github.com/NouraAlgohary/FIFA-World-Cup-Data-Analysis/assets/103903785/20fe045a-b17b-44dc-a299-1c305ed5aaec)

No. of teams
![image](https://github.com/NouraAlgohary/FIFA-World-Cup-Data-Analysis/assets/103903785/86f5c2ed-b2d9-4031-84ce-7cf2f9f27e9e)

### 3. Data Cleaning and ETL:
- Profile and clean the extracted data.
- Perform Extract, Transform, and Load (ETL) operations to structure the data for analysis.
- Load the following fields:
Year
Host Country
Champion
Runner-up
Final Score
Number of Teams

![image](https://github.com/NouraAlgohary/FIFA-World-Cup-Data-Analysis/assets/103903785/31d23f60-34fb-4b4b-a778-20b4c507acba)

### 4. Report Visualization:
I chose appropriate visuals to convey the following insights:</br>
a. Host Country Frequency: </br>
&emsp;Display the number of times the championship was hosted by the host country  on a map. </br>
b. Top 5 World Cup Winners:</br>
&emsp;Highlight the top 5 countries that have won the World Cup the most.</br>
c. Teams Participation:</br>
&emsp;Showcase the number of teams that participated in each championship.</br>
d. Detailed Table:</br>
&emsp;Create a table displaying all the relevant fields in a clear and organized manner.</br>
e. Yearly Filtering:</br>
&emsp;Implement a filter mechanism allowing users to filter the dashboard by year.</br>

_This documentation serves as a guide for project execution, ensuring a systematic approach to extracting, processing, and visualizing FIFA World Cup data for meaningful insights._
