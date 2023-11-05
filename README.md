# HackNJIT-2023
## Inspiration
In their marine science-focused high school, Darren and John learned about the climate issues affecting vital areas of the environment. This includes coral bleaching, which is an important issue, especially in the Caribbean, caused by the rising climate. As CO2 is the driving cause of the rising temperatures, it follows that a correlation between the two is possible.

## What it does
Our project is a website that was built and hosted using GoDaddy. It has two main features: a chatbot and interactive maps. The chatbot provides general information about the Caribbean and coral bleaching to any interested users. The first interactive map shows the coral bleaching severity in reefs inside the Caribbean, and the second interactive map shows the CO2 emissions of the countries nearest to the reef in that year.

## How we built it
To create the interactive maps, our first step was to collect data. We found our first dataset about global coral reef data on Zenodo, and we found our second dataset about carbon emissions records by country on Kaggle. We used Pandas to filter the data sets to what we needed, and then we merged them by country and year. Using the filtered data, we used Folium to create HTML files for the interactive maps that we embedded into the website.
To create the chatbot, we used Kommunicate.io, which is a chatbot builder. It helped us train it and it provided HTML that we used to integrate the chatbot into our website.
To host the website, we registered a domain through GoDaddy. Then, we created the website mainly using the GoDaddy website builder, and we also used it to integrate our interactive maps and the chatbot.

## Challenges we ran into
- We ran into an issue with Folium displaying data from before and after 2001. On its GitHub, we found a thread about this issue that said it was caused by the unix epoch time having a different number of digits from 2001 to 2002

## Languages used
Python, Javascript

## Packages used
Python Pandas, Folium

## Code Resources
- Bleaching Data- https://zenodo.org/records/6780843 
- Tourism Data- https://data.worldbank.org/indicator/ST.INT.ARVL?end=2019&locations=ZJ&start=1995
- CO2 Data- https://zenodo.org/records/7215364
- Chatbot- https://kommunicate.io
- GoDaddy- https://www.godaddy.com/

## Website Sources
- https://www.sciencedirect.com/topics/earth-and-planetary-sciences/caribbean-sea
- https://ecowatch.noaa.gov/regions/caribbean
- https://ecowatch.noaa.gov/regions/caribbean
- https://earthjustice.org/article/coral-reefs-and-the-unintended-impact-of-tourism
- https://marine-conservation.org/on-the-tide/how-well-are-coral-reefs-protected/
- https://coastalscience.noaa.gov/project/national-coral-reef-monitoring-program-biological-socioeconomic/
- https://www.nature.com/articles/s41597-022-01121-y#Sec4
