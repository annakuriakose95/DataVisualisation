The Portfolio_201754454.html contains the entire code and visualisations. However, due to .html rendering issues for certain figues like the geospacial, sankey, widgets etc. These are attached as seperate .html files for reference and the widgets are included as a working video for clarity.

TABLE OF CONTENTS

INTRODUCTION
DATA
DATA PREPROCESSING
TYPES OF VISUALISATIONS
CONCLUSION
BIBLIOGRAPHY

INTRODUCTION
In a world filled with data, the ability to transform complex information into clear and engaging visuals is essential. One way to extract information from data is to visualize it in a way that conveys the desired messages accurately, without misleading like a scientist, and is aesthetically pleasing like a designer (Wilke, 2019). This visualization portfolio offers a collection of interesting visual stories derived from data that is raw. Beyond charts and graphs, each visualization exhibit insights, trends, and patterns essential for conveying message effectively to the indended audience. This portfolio offers a rich display of versatile and effective visualizations that highlight the impact of visual storytelling like geospacial, widgets, wordcloud, correlation pair plots, box plots, animating plots as well as line, bar and pie plots. I am planning to showcase multiple types of visualisations using five different datasets taken from multiple sources.

DATA
Crimes dataset (Asaniczka, 2024) is a collection of official crime records reported in Los Angeles City from 2020-2023 publicly accessible via the Los Angeles City Open Data portal (Los Angeles - Open Data Portal, n.d.). The aim is to visualise data from multiple catagorical variables where no direct counts involved in the dataset which makes it complex to visualise it. (World Population by Country 2024 (LiVE), n.d.) found in kaggle (World Data Population, 2024) is used for exploring interactive geospacial animation, (Global Ecological Footprint 2023, 2024) dataset sorced from (Data and Methodology - Global Footprint Network, 2024) to plot geospatial as well as scatter pairplot to display correlation and emotion dataset from hugging face (Hugging Face, 2023) available through kaggle (Emotion Dataset for Emotion Recognition Tasks, 2021) to display interactive widgets and display word cloud. Lastly, I have taken the UK elections dataset of 2017 (General Election 2017, 2019) and 2019 (General Election 2019, 2020) which is concatenated to create a Sankey diagram displaying changes in voter proportion across different political parties over these years. This I am demostrating as an attempt in which I critically evaluate it for future work.


TYPES OF VISUALISATIONS:
Bar Plot
Box Plot
Line Plot
Pie Chart
Geospatial Plot
Pair Plot
Widgets
Word Cloud
Sankey Diagram


CONCLUSION
My data visualization portfolio demonstrates the ability to interpret and present complex datasets using various plotting techniques of matplotlib and seaborn. Key insights include the predominance of young adult victims in crime reports and the similar age distributions in vandalism cases for both genders. Trends in serious and lesser offenses over recent years are highlighted, along with the geographical distribution of crimes in LA. Global population growth and economic aspects are effectively visualized using animated and scatter geo plots. Interactive widgets and word clouds enhance user engagement by showcasing frequent words associated with emotions. Lastly, the Sankey diagram illustrates political shifts in the UK between 2017 and 2019. Each visualization provides clear, actionable insights, ensuring complex data is interpretable.

BIBLIOGRAPHY
Wilke, C. O. (2019). Fundamentals of Data Visualization. Claus O. Wilke. https://clauswilke.com/dataviz/introduction.html
Asaniczka. (2024, February 17). Los Angeles Crime Data 2020-2023. Kaggle. https://www.kaggle.com/datasets/asaniczka/crimes-in-los-angeles-2020-2023/data
Datala: Information, insights, and analysis from the City of Angels: Los Angeles - open data portal. City of Los Angeles. (n.d.). https://data.lacity.org/
Offense definitions. (n.d.). FBI. https://ucr.fbi.gov/crime-in-the-u.s/2011/crime-in-the-u.s.-2011/offense-definitions

General Election 2019: full results and analysis. (2020, January 28). UK Parliament. https://commonslibrary.parliament.uk/research-briefings/cbp-8749/
General Election 2017: full results and analysis. (2019, January 29). UK Parliament. https://commonslibrary.parliament.uk/research-briefings/cbp-7979/
Global Ecological Footprint 2023🌐[latest report]. (2024, May 17). Kaggle. https://www.kaggle.com/datasets/jainaru/global-ecological-footprint-2023/data
Data and Methodology - Global Footprint Network. (2024, February 16). Global Footprint Network. https://www.footprintnetwork.org/resources/data/
dair-ai/emotion · Datasets at Hugging Face. (2023, March 22). https://huggingface.co/datasets/dair-ai/emotion
Emotion Dataset for emotion recognition tasks. (2021, September 15). Kaggle. https://www.kaggle.com/datasets/parulpandey/emotion-dataset?select=training.csv
pandas.to_datetime — pandas 2.2.2 documentation. (n.d.). https://pandas.pydata.org/docs/reference/api/pandas.to_datetime.html
House of Commons Library. (2023, March 24). Pensioner poverty. Commons Library Research Briefing. https://commonslibrary.parliament.uk/research-briefings/cbp-8749/
Decoding UK elections with interactive visualizations. (2024, January 16). Flourish. https://flourish.studio/blog/visualizing-uk-elections/
seaborn.barplot — seaborn 0.13.2 documentation. (n.d.). https://seaborn.pydata.org/generated/seaborn.barplot.html
pandas.DataFrame.melt — pandas 2.2.2 documentation. (n.d.). https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.melt.html

World Population by Country 2024 (LiVE). (n.d.). https://worldpopulationreview.com/
World data population. (2024, January 12). Kaggle. https://www.kaggle.com/datasets/tanishqdublish/world-data-population/data
How to suppress Pandas Future warning? (n.d.). Stack Overflow. https://stackoverflow.com/questions/15777951/how-to-suppress-pandas-future-warning
Offense Definitions. (2019). https://ucr.fbi.gov/crime-in-the-u.s/2019/crime-in-the-u.s.-2019/topic-pages/offense-definitions
x axis gets transformed to floats. (n.d.). Stack Overflow. https://stackoverflow.com/questions/48715330/x-axis-gets-transformed-to-floats

normalize a column to represent it as a size in a scatter plot. (n.d.). Stack Overflow. https://stackoverflow.com/questions/50310059/normalize-a-column-to-represent-it-as-a-size-in-a-scatter-plot
Solanki, S. (2022, August 1). How to Create Sankey Diagrams (Alluvial) in Python (holoviews & plotly)? https://coderzcolumn.com/tutorials/data-science/how-to-plot-sankey-diagram-in-python-jupyter-notebook-holoviews-and-plotly?source=post_page-----4b7a7841f050--------------------------------
pandas.DataFrame.apply — pandas 2.2.2 documentation. (n.d.). https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.apply.html
