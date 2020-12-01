# Capstone
We will use data science to figure out the neighbourhoods of Delhi which could be the optimum location for starting a new Italian restaurant.

Steps of the Project:
1) Dataset- The neighborh data for this problem was collected by web scrapping using BeautifulSoup library. The venues data was extracted using Foursquar API using the location data of each neighborhood.  
2) Data Exploration-The popular venues for each neighborhood were added to each and they were classified into different categories.
3) Segmentation- The neighborhoods were segmented into 7 clusters based on the popular venues for the neighborhoods and the maps were visulaized using Folium.
4) Cluster Analysis: Each cluster was further explored and the number of Italian restaurants in one of the clusters on average were found to be much higher than the rest. The neighborhoods having the least number of Italian restaurants while being in this cluster were optimum for starting a new business.

Results:
The most optimum neighborhoods are- Keshav Puram, Punjabi Bagh, Patel Nagar
