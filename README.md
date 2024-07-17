# tableau-challenge-citi-bike

![Screenshot 2024-07-17 105355](https://github.com/user-attachments/assets/98b60280-bbb7-4c25-8759-9dc02c484443)

# Background
Data analysis and visualization of Citi Bike data (https://www.citibikenyc.com/system-data) was performed for overseeing the bike-sharing program at Citi Bike NYC (https://en.wikipedia.org/wiki/Citi_Bike). 

Before the analysis, the data was combined by month, cleaned and transformed by using pandas. The data was then analyzed, visualized, and published using Tableau. Due to the data size limitation, only the data of three months (2023_Aug, 2023_Sep, and 2023_Nov) were used for the analysis. Due to large size of the data, the original data together with Jupyter Notebook and processed csv files are saved on Google Drive with the link: https://drive.google.com/drive/folders/1ViKzXKeh6UDTiEwxMPDmER3MW211Jp-b?usp=sharing

# Viusalization presentation

Five visualizations can be accessed by the link of Tableau public 
https://public.tableau.com/app/profile/yi.wen7753/viz/citi-bike_v2024_1/Citi-BikeDataVisualization?publish=yes

# Analysis and key insights

1. Two types of trip displays of the trips between a popuplar start station and its asssociated end stations. The distance (miles), time, station name/ID of each trip are shown in the marker. 

![Trip Displays](https://github.com/user-attachments/assets/a23dc483-44c3-4acc-877b-731530b212dd)

2. All bike stations inluding start and end stations are displayed on the map. The popularity of each station is indicated by color, size, shape. The station name / ID and location are shown in the marker.
Sections are marked by zip code on the map. The description is shown under the map.

![Map of stations](https://github.com/user-attachments/assets/87501128-cd85-419d-8481-cb307815707e)

3. The most and least popular stations are displayed in the horizontal bar chart. The station name and trip counts are shown in the chart. The analysis is written in the text box under the chart.

![MemberCasual](https://github.com/user-attachments/assets/e55ff5f8-a8f9-4f61-b60e-fca03093f29f)

4. The count and percentage of members and casual riders are displayed in the bar chart. The associated analysis is in the text box under the chart.

![TopBottomStations](https://github.com/user-attachments/assets/c321f5b6-b142-44a2-b9dd-2696dd44664f)

5. The peak and valley hours are displayed in the line chart. The visualization provides information about when the bike can be more available for the riders. 

![PeakValleyHours](https://github.com/user-attachments/assets/0fe528f5-90f5-4e7f-939c-e6c82fbc1318)
