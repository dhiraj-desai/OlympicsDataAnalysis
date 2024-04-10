<h1>Exploratory Data Analysis: 120 Years of Olympics History - <a href="https://olympicsanalysiswithdhiraj.netlify.app/">Python Web App</a></h1>

<h3>Intrdouction</h3>
<p>This is an Exploratory Data Analysis project to analyze the modern Olympic Games, including all the Games from Athens 1896 to Rio 2016. This analysis provides an opportunity to ask questions about how the Olympics have evolved over time, including questions about the participation and performance of women, different nations, and different sports and events.</p>


<h3>Data Source</h3>
<p>The dataset is collected from here. The dataset contains two files: athlete_events.csv and noc_regions.csv.
The file athlete_events.csv contains 271116 rows and 15 columns. Each row corresponds to an individual athlete competing in an individual Olympic event (athlete events). The columns are:

ID - Unique number for each athlete
Name - Athlete's name
Sex - M or F
Age - Integer
Height - In centimetres
Weight - In kilograms
Team - Team name
NOC - National Olympic Committee 3-letter code
Games - Year and season
Year - Integer
Season - Summer or Winter
City - Host city
Sport - Sport
Event - Event
Medal - Gold, Silver, Bronze, or NA


The file noc_regions.csv contains 230 rows and 3 columns. Each row corresponds to an individual region. The columns are:
NOC (National Olympic Committee 3 letter code)
region
notes
</p>


<h3>Python Web App</h3>
<p>This project is deployed on Streamlit Community Cloud. You can access the web app here.
Note: All the graphs and charts are interactive. You can hover over the graphs and charts to get more information. You can also download the graphs and charts in png format.</p>

<h3>Features of the Web App</h3>
<p>The web app provides a brief overview of the dataset. It provides users to choose between 4 options to explore the dataset. The options are:

Medal Tally
Overall Analysis
Country-wise Analysis
Athlete-wise Analysis
</p>


<h3>Medal Tally</h3>
<p>This section provides the medal tally of all the countries that have participated in the Olympics. The medal tally is displayed in a table format. The table can also be filtered by selecting the Country Name and Year from the dropdown list.</p>

<h3>2. Overall Analysis</h3>
<p>This section provides the overall analysis of the Olympics. It provides information like:

Top Statistics of the Olympics (Edition, Hosts, Sports, Events, Nations, Athletes)
No. of countries participating in the Olympics over the years (Line Graph)
No. of events organized over the years (Line Graph)
No. of athletes participating over the years (Line Graph)
Correlation between the no of Events for each and every Sport w.r.t Year (Heatmap)
Table of top 15 athletes who have won the most number of medals in the Olympics. This table can also be filtered by selecting the Sports Name from the dropdown list.</p>


<h3>3. Country-wise Analysis</h3>
<p>This section provides a country-wise analysis of the Olympics. It contains a dropdown list where user can select Country Name, based on that the section will display the following information:

Medal Tally over the years for that country (Line Graph)
In which sport does the country excel the most (Heatmap)
Top 10 athletes of that country (Table)
</p>


<h3>4. Athlete-wise Analysis</h3>
<p>This section provides an athlete-wise analysis of the Olympics.

Distribution of Age of the athletes for Winning Medals (Curves)
Distribution of Age w.r.t Sports only who have won Gold Medals (Curves)
Distribution of Age w.r.t Sports only who have won Silver Medals (Curves)
Men Vs Women Participation Over the Years (Line Graph)</p>



